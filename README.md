# HMurakami-lab GitHub Organization Profile

This folder is prepared to become the special GitHub organization profile
repository for `HMurakami-lab`.

GitHub shows the contents of `profile/README.md` on the organization's Overview
page when this folder is published as:

```text
https://github.com/HMurakami-lab/.github
```

## Publish Steps

1. Create or open the `HMurakami-lab` organization on GitHub.
2. Make sure your account has permission to create repositories in that
   organization. If not, an organization owner needs to add you first.
3. Create a public repository under that organization named exactly `.github`.
4. Push this folder to that repository.
5. Visit `https://github.com/HMurakami-lab` and check the Overview page.

Using GitHub CLI from this folder, the publish command would be:

```bash
git init
git add README.md profile/README.md
git commit -m "Add organization profile README"
gh repo create HMurakami-lab/.github --public --source=. --remote=origin --push
```
