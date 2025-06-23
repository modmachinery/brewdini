# 🧞 (The Great) Brewdini
This is The Great Brewdini. He can only grant one wish: Updating your Homebrew formulae and Casks.

## What Brewdini does
Brewdini mixes a combination of built-in Homebrew commands with [homebrew-cask-upgrade](https://github.com/buo/homebrew-cask-upgrade) by [buo](https://github.com/buo).

After the updates are completed he runs `brew doctor`. If all commands succeed, he will then clean up and prune all downloads.

## Usage
```console
brewdini [-option] [--option]
```

## Options
* `-a`, `--all`

   Include apps that auto-update in the upgrade

* `-f`, `--force`

   Force-reinstall apps that are marked as 'latest'

* `-i`, `--interactive`

   Run updates in interactive mode
