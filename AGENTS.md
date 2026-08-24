# what to do after every change
- add, commit and push
- Pushing `main` triggers the normal Vercel deployment through the GitHub integration; verify that deployment and the live site after each push.
- Use the Vercel CLI only for manual deployments or troubleshooting. CLI authentication is not required for GitHub-triggered deployments.

# image conversion
- For HEIC photos, use `qlmanage -t` to make a PNG first, then convert that PNG to JPG with `sips`; direct HEIC to JPG via `sips` can produce a black image.
