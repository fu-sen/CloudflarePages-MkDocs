## CloudflarePages-MkDocs

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

## Build error

Currently targeting **build system version 2**.

To change from build system version 1 to version 2:

https://developers.cloudflare.com/pages/configuration/build-image/#v1-to-v2-migration

If you must continue to use version 1 of the build system,
your `runtime.txt` should look like this:

```
3.7
```

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.
