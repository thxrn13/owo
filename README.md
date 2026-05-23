# owo_cli

A tool to alias [`thefuck`](https://github.com/nvbn/thefuck) to `owo` (any system) 
and `sudo $(fc -ln -1)` to `pwease` (on Unix). This allows the user to use `owo` in place of `thefuck`
and `pwease` to rerun their previous command with elevated permissions.

## Requirements

- [thefuck](https://github.com/nvbn/thefuck)
    - Follow installation instructions provided by the publisher

## Installation

### PyPI
```shell
pip install owo_cli
```

## Usage

### Unix (Linux/MacOS)

```shell
owo_cli [--shell_file|-sf path_to_shell_config]
```
Defaults to `~/.[shell]rc` where `shell` is the shell you are using.

#### This installs both aliases

### Windows

This will *only* install the alias for thefuck

```shell
owo_cli
```
