# GitHub URL Tricks and Alternative Web Viewers

> A general-purpose GitHub reference for browsing repositories, viewing code, exploring file history, and using online development tools. This guide is not part of the BIT study materials or any semester syllabus.

## 1. Repository URL transformations

Start with a repository URL in this format:

```text
https://github.com/OWNER/REPOSITORY
```

| Feature / purpose | URL modification | What it does |
|---|---|---|
| Repository architecture diagram | Replace `github.com` with `gitdiagram.com` | Creates an interactive diagram to help explore a repository's structure and relationships. |
| Browser-based VS Code editor | Replace `github.com` with `github.dev` | Opens the repository in a VS Code-like editor in the browser. |
| Alternative code viewer | Replace `github.com` with `github1s.com` | Opens a VS Code-style interface for browsing repository files. |
| AI-friendly repository text | Replace `github.com` with `gitingest.com` | Converts accessible repository content into consolidated text for AI-assisted analysis. |
| AI-generated repository documentation | Use `https://deepwiki.com/OWNER/REPOSITORY` | Provides AI-generated explanations and documentation for supported repositories. |
| Repository context for compatible AI tools | Use `https://gitmcp.io/OWNER/REPOSITORY` | Makes repository information available to compatible AI assistants through an MCP service. |
| File history visualization | Use `https://github.githistory.xyz/OWNER/REPOSITORY/blob/BRANCH/PATH` | Shows how an individual file has changed across commits. |
| Online development environment | Use `https://stackblitz.com/github/OWNER/REPOSITORY` | Opens supported projects in StackBlitz; compatibility depends on the project's framework and configuration. |
| Raw file content | Replace `github.com/OWNER/REPOSITORY/blob/BRANCH/PATH` with `raw.githubusercontent.com/OWNER/REPOSITORY/BRANCH/PATH` | Displays the file as raw text without GitHub's normal file-view page. |

## 2. File, Markdown, history, and download shortcuts

| Feature / purpose | URL modification | What it does |
|---|---|---|
| Show Markdown source | Add `?plain=1` to a file URL | Displays the Markdown source rather than its rendered view. |
| Jump to a line | Add `#L10` | Opens a file at line 10. |
| Highlight a line range | Add `#L10-L20` | Highlights lines 10 through 20 in a file. |
| View file commit history | Change `/blob/` to `/commits/` in a file URL | Shows commits that changed that file. |
| View line-by-line authorship | Change `/blob/` to `/blame/` | Shows who last modified each line. |
| Download the main branch as ZIP | Append `/archive/refs/heads/main.zip` to the repository URL | Downloads the main branch as a ZIP archive. Replace `main` if the branch has a different name. |
| Download the main branch as TAR.GZ | Append `/archive/refs/heads/main.tar.gz` | Downloads the main branch as a compressed TAR archive. |
| View a pull request diff | Add `.diff` to a pull request URL | Displays the proposed changes in unified diff format. |
| Download a pull request patch | Add `.patch` to a pull request URL | Provides the proposed changes as a patch. |
| Create a permanent file link | Open a file and press `Y` | Changes the branch reference to a commit-specific link, so it continues to refer to that exact version. |

## 3. Useful GitHub keyboard shortcuts

Keyboard shortcuts generally work when focus is not inside a text input. Press `?` on GitHub to view the current shortcut reference.

| Shortcut | Purpose |
|---|---|
| `.` (period) | Open the current repository in github.dev. |
| `T` | Open the repository file finder. |
| `W` | Open the branch selector. |
| `Y` | Convert the current file URL to a commit-specific permalink. |
| `B` | Open the blame view for the current file. |
| `G`, then `C` | Go to the repository Code page. |
| `G`, then `I` | Go to Issues. |
| `G`, then `P` | Go to Pull Requests. |
| `?` | Display GitHub's keyboard shortcut reference. |

## 4. Example URLs

The following examples use a public repository. Replace the owner and repository name with the ones you want to explore.

| Purpose | Example |
|---|---|
| Original GitHub repository | [github.com/2narl/BitPU_StudyPlan](https://github.com/2narl/BitPU_StudyPlan) |
| Architecture diagram | [gitdiagram.com/2narl/BitPU_StudyPlan](https://gitdiagram.com/2narl/BitPU_StudyPlan) |
| Browser VS Code editor | [github.dev/2narl/BitPU_StudyPlan](https://github.dev/2narl/BitPU_StudyPlan) |
| Alternative code viewer | [github1s.com/2narl/BitPU_StudyPlan](https://github1s.com/2narl/BitPU_StudyPlan) |
| AI-friendly repository text | [gitingest.com/2narl/BitPU_StudyPlan](https://gitingest.com/2narl/BitPU_StudyPlan) |
| AI-generated documentation | [deepwiki.com/2narl/BitPU_StudyPlan](https://deepwiki.com/2narl/BitPU_StudyPlan) |
| AI repository context | [gitmcp.io/2narl/BitPU_StudyPlan](https://gitmcp.io/2narl/BitPU_StudyPlan) |

## 5. Recommended tools

| Tool | Best use | Website |
|---|---|---|
| GitDiagram | Visualizing repository structure | [gitdiagram.com](https://gitdiagram.com) |
| github.dev | Browsing and editing files in a browser | [github.dev](https://github.dev) |
| Gitingest | Preparing repository text for AI analysis | [gitingest.com](https://gitingest.com) |
| DeepWiki | Exploring AI-generated documentation | [deepwiki.com](https://deepwiki.com) |
| StackBlitz | Running supported projects online | [stackblitz.com](https://stackblitz.com) |

## 6. Security and usage notes

- Third-party viewers are not necessarily official GitHub services. Check their privacy policies and terms before using them.
- Do not submit passwords, access tokens, private repository links, or confidential source code to third-party services unless you have verified that the service is appropriate and secure.
- Some tools may require sign-in, may not support private repositories, or may change their URL behavior over time.
- A repository being public does not guarantee that every external viewer will index or display it correctly.
- GitHub keyboard shortcuts and interface behavior may vary by page and can change. Use GitHub's `?` shortcut reference for the latest list.

---

*This document is a general GitHub and developer-tool reference. It is separate from the repository's university study plans, syllabuses, notes, and previous-question materials.*
