# 🧞 brewdini
This is The Great Brewdini. He only grants one wish; he updates your Homebrew formulae and Casks.

## What it does
Utilizes built-in Homebrew commands, and [homebrew-cask-upgrade](https://github.com/buo/homebrew-cask-upgrade) by [buo](https://github.com/buo).

Performs `brew doctor`, then automatically cleans up after itself if all commands succeed.

## Usage

`brewdini [-option] [--option]`

## Options

	-a, --all		Include apps that auto-update in the upgrade
	-f, --force		Force-reinstall apps that are marked as 'latest'
	-i, --interactive	Run updates in interactive mode
