# Multi-Git Manager

VS Code extension for working with several Git repositories in one workspace.

## Features

- Overview and live status of all repositories in the workspace
- Bulk pull, push and fetch
- Branch switching and creation across repositories
- Custom Git commands run against multiple repositories

## Installation

Install from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=ElanZhou.vscode-multi-git-manager).

## Usage

1. Open a workspace that contains multiple Git repositories.
2. Click the Multi-Git Manager icon in the Activity Bar.
3. Use the toolbar for bulk actions: Refresh, Pull All, Push All, Fetch All. Click a repository for single-repository actions.

## Settings

```json
{
  "multiGitManager.autoRefresh": true,
  "multiGitManager.refreshInterval": 300,
  "multiGitManager.showNotifications": true
}
```

## Development

```bash
yarn install
yarn compile    # then press F5 in VS Code to launch the Extension Development Host
```

`LEGAL.md` holds the legal notice. The `python_cli/` directory contains a command-line companion.
