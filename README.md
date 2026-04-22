# taskflow-link

This repository serves as a **metadata wrapper** and **smart redirector** for the **Taskflow** project.

### Purpose
LinkedIn's "Featured" section often defaults to generic thumbnails (like the Devpost logo) when adding external links. This repository hosts custom [Open Graph (OG)](https://ogp.me/) tags and a high-fidelity thumbnail to ensure the project looks professional on social platforms.

### How it works
1. **Metadata:** The `index.html` file contains specific `<meta>` tags that LinkedIn's crawler reads to display a custom image, title, and description.
2. **Redirect:** Upon clicking the link, the user is instantly redirected to the official [Taskflow Devpost page](https://devpost.com/software/taskflow-qv6z7m).

### Project Context
**Taskflow** was the **Atlassian Track Winner** at DubHacks 2025. It is an AI-driven productivity tool that uses OpenAI OCR and Atlassian Rovo to automate Jira task creation from simple screenshots.
