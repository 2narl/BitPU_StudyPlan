# Student Management System (C++ & SQLite3)

A simple console-based CRUD project to test database connectivity using C++ and SQLite3.

## Project Structure
- `main.cpp` — Complete C++ source (class `StudentDB` wraps all DB logic)
- `schema.sql` — Table schema + sample SQL queries for reference
- `students.db` — SQLite database file (auto-created on first run)

## Database Schema

```sql
CREATE TABLE students (
    id       INTEGER PRIMARY KEY AUTOINCREMENT,
    name     TEXT    NOT NULL,
    roll_no  TEXT    NOT NULL UNIQUE,
    age      INTEGER NOT NULL CHECK(age > 0),
    course   TEXT    NOT NULL,
    gpa      REAL    DEFAULT 0.0 CHECK(gpa >= 0.0 AND gpa <= 4.0)
);
```

## Compilation Instructions

### 1. Install SQLite3 development library (if not already installed)
```bash
sudo apt-get update
sudo apt-get install libsqlite3-dev
```

### 2. Compile with g++
```bash
g++ main.cpp -o student_app -lsqlite3 -std=c++17
```
- `-lsqlite3` links the SQLite3 library — required, or you'll get "undefined reference" errors.
- `-std=c++17` enables modern C++ features used in the code.

### 3. Run
```bash
./student_app
```

A `students.db` file will be created automatically in the same folder, and a menu-driven interface will let you Add, View, Search, Update, and Delete student records.

## How the Code Works (Quick Reference)

| Function | SQL Concept | Notes |
|---|---|---|
| `createTable()` | `CREATE TABLE IF NOT EXISTS` | Runs once at startup |
| `insertStudent()` | `INSERT INTO ... VALUES (?,?,?,?,?)` | Uses prepared statements (prevents SQL injection) |
| `readAllStudents()` | `SELECT * FROM students` | Loops with `sqlite3_step()` |
| `findByRollNo()` | `SELECT ... WHERE roll_no = ?` | Parameterised lookup |
| `updateStudent()` | `UPDATE ... SET ... WHERE roll_no = ?` | Checks `sqlite3_changes()` to confirm a row was affected |
| `deleteStudent()` | `DELETE FROM ... WHERE roll_no = ?` | Same affected-row check |

Error handling is done throughout via `sqlite3_errmsg(db)` and return-code checks (`rc != SQLITE_OK` / `SQLITE_DONE`), so connection failures, bad queries, or constraint violations are reported clearly instead of crashing silently.

## Testing / Verification
The program was compiled and tested end-to-end (insert, read, update, delete, including edge cases like deleting a non-existent roll number) — it worked correctly with no errors.
