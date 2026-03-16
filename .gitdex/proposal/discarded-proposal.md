# Discarded-Proposal

- Consider adding a simple MkDocs site to showcase the project documentation in a structured way, and deploy it to GitHub Pages automatically.
- Introduce a semantic versioning strategy using standard-version or npm version if a Node.js component is added in the future.
- Explore setting up Dependabot alerts for vulnerability scans on all dependencies, even if the current repo has none yet.
- Create .github/ISSUE_TEMPLATE/config.yml that references bug_report.md, feature_request.md, and feedback.md templates
- Create .github/ISSUE_TEMPLATE/feedback.md with fields: Feedback Type, Description, Environment
- Create a Dockerfile that uses nginx to serve the existing index.html at /usr/share/nginx/html
- Create a GitHub Projects v2 board named "Project Board" with columns "Backlog", "In Progress", and "Done" via the GitHub API
- Create .github/settings.yml to enable Discussions for this repository
- Create .github/workflows/security.yml that runs CodeQL analysis on every pull request to detect vulnerabilities
- Create .github/workflows/pre-commit.yml that runs pre‑commit hooks automatically on push and pull_request events
- Create a docs/ folder with a minimal MkDocs configuration, then create .github/workflows/deploy-docs.yml that builds the MkDocs site and deploys it to GitHub Pages on each push to master
- Create .github/workflows/release-automated.yml that automatically generates a semantic release tag (vX.Y.Z) and changelog based on Conventional Commits whenever new commits exist since the last tag
