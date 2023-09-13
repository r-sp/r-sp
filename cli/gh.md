# GitHub CLI

GitHub CLI is an open source tool for using GitHub from your computer's command line. When you're working from the command line, you can use the GitHub CLI to save time and avoid switching context.

GitHub CLI includes GitHub features such as:

- View, create, clone, and fork repositories
- Create, close, edit, and view issues and pull requests
- Review, diff, and merge pull requests
- Run, view, and list workflows
- Create, list, view, and delete releases
- Create, edit, list, view, and delete gists
- List, create, delete, and connect to a codespace

GitHub CLI, or `gh`, is a command-line interface to GitHub for use in your terminal or your scripts.

For more information about what you can do with GitHub CLI, see the [GitHub CLI manual](https://cli.github.com/manual).

## Installing GitHub CLI

For installation instructions for GitHub CLI, see the [GitHub CLI repository](https://github.com/cli/cli#installation).

- [Available commands](https://cli.github.com/manual/gh)
- [Usage examples](https://cli.github.com/manual/examples)
- [Community extensions](https://github.com/topics/gh-extension)

---

## Commands

### login

```sh
gh auth login
gh auth login --with-token < mytoken.txt
```

### browse

```sh
gh browse [<number> | <path> | <commit-SHA>] [flags]
```

### codespace

```sh
gh codespace create
gh codespace code --web
```

### gist

```sh
gh gist list
gh gist create --public index.js
gh gist view [<id> | <url>] [flags]
```

### issues

```sh
gh issue list
gh issue create
gh issue status
gh issue view 1
```

### pr

```sh
gh pr list
gh pr create
gh pr view 27
gh pr review 5
gh pr merge 1
```

### repo

```sh
gh repo create
gh repo clone r-sp/cc
gh repo list r-sp
gh repo fork r-sp/cc
gh repo view r-sp/cc
```

### workflow

```sh
gh workflow list
gh workflow run build.yml
gh workflow view
gh workflow enable build.yml
gh workflow disable build.yml
```

### run

```sh
gh run list
gh run view
gh run watch 2751
gh run cancel 2751
gh run rerun 2751
```

### status

```sh
gh status
```
