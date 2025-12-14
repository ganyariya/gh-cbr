# gh-cbr

A GitHub CLI extension for interactively checking out Git branches with a fuzzy finder. 🚀

## Features

- **Interactive Selection with fzf**: Uses `fzf` for fuzzy searching and selecting branches from a list. 🔍
- **Prioritizes Recently Worked Branches**: Displays branches in order of recency:
  - Recently checked out branches (RECENT) 🕒
  - Local branches (LOCAL) 🏠
  - Remote branches (REMOTE) 🌐
- **Preview Display**: Shows a preview of the selected branch's git log in a side window. 👀

## Dependencies

- gh
- `fzf` (fuzzy finder)

## Installation

```bash
gh extension install ganyariya/gh-cbr
```

## Usage

```bash
gh cbr
```
