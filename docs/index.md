# CloudflarePages-MkDocs

<https://github.com/fu-sen/CloudflarePages-MkDocs>

**MkDocs with Cloudflare Pages (minimal configuration)**

- [Cloudflare Pages](https://pages.cloudflare.com/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. Commit to a GitHub project: `git push`
4. Create a project from Cloudflare Pages and select your GitHub project.
5. Enter the following items and select **Create Static Site**:
    - **Project name**: Any name
    - **Production branch**: `main`, `master`, etc.
    - **Framework preset**: `Mkdocs`
6. Wait a moment. `Success: Your site was deployed!` is displayed and the deployment is complete.
