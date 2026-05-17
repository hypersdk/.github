# hypersdk organization profile

GitHub shows this content on **[github.com/hypersdk](https://github.com/hypersdk)** when published to the **`hypersdk/.github`** repository as `profile/README.md`.

This is **separate** from **[hypersdk/hypersdk](https://github.com/hypersdk/hypersdk)** `README.md`, which stays technical and Community Edition–focused.

## Publish

```bash
cd hypersdk-org-profile
git init
git add profile/README.md
git commit -m "Add organization profile README"
gh repo create hypersdk/.github --public --description "HyperSDK GitHub organization profile" --source=. --remote=origin --push
```

If the repo already exists, push `profile/README.md` to `main` on `hypersdk/.github`.
