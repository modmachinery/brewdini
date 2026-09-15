# 🧞 Brewdini
This is *The Great Brewdini*. He can grant one specific wish:
### *"Update all my Homebrew Formulae & Casks in a single command!"*

## What Brewdini does
- Runs `brew update` to check for pending updates; automatically runs `brew upgrade` if so
- If all commands succeed, runs `brew cleanup --prune=all`
- Will also run `brew doctor` if the `--check` option is called

## Usage

```bash
brewdini [-option] [--option]
```

## Options
|Option|Action|
|-|-|
|`-h`, `--help`| Displays help & usage |
|`-f`, `--force`| Force-upgrade Formulae & Casks marked as 'latest' |
|`-c`, `--check`| Runs 'brew doctor' after updates complete to check Homebrew |
