# kraftcss
kraftcss
If you encounter the error `ERR_OSSL_EVP_UNSUPPORTED` you can do :

```bash
export NODE_OPTIONS=--openssl-legacy-provider
npm i --force
npm run dev
```- Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) when applicable (recommended but not required)
- Always use present tense in commit messages
- Always review your changes before committing
- A pre-commit hook type checks the code base. If it fails but you want to commit a WIP anyway use `--no-verify`- Always create a draft PR right away when starting to work on a new branch
- Vercel creates a unique link for each commit and each branch (showing the latest version of the branch), which you can get from the deployment page. Share the branch link with the team if needed
- Always self-review changes in your PR before asking others. Refactor, clean up and add comments if needed. Repeat until there's no room for improvement that you see, or you've left a comment where there is
- If you consider it ready, mark it as ready for review and ask for a review, or merge it by yourself if you have the permission
