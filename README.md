# vscode-run-diff

## Features

Use the `alt+shift+z` keybinding to run your active Python file and diff expected versus actual program output:

![Run code and diff expected vs actual program output](./images/without_prompt.gif)

## Requirements

Ensure that you have `python3` on PATH, pointing to a valid [Python 3](https://python.org) installation.

## Extension Settings

This extension contributes one setting, `vscode-run-diff.expectedOutputFilePath`: Path to a file containing expected program output. 

![Configure setting to skip prompt on each run](./images/setting.gif)

If this setting is omitted, you will be prompted to select the file containing expected program output from the system file picker dialog on each run:

![Prompt when setting is not configured](./images/with_prompt.gif)

