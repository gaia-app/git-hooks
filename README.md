# hooks

This repository contains the hooks we use at `Gaia` in our development process.

## installation

Clone this repository somewhere :

```bash
git clone git@github.com:gaia-app/git-hooks.git
```

### Global setup (for all your repositories)

Enter the hooks directory and setup your hooks globally :

```bash
cd hooks
git config --global core.hooksPath $PWD/git-hooks
```

### Local setup (for a repository only)

Enter the repository you want to manage with the hooks, and run :

```bash
git config core.hooksPath <path-to-cloned-repo>
```
