homebrew
========

Ensure that homebrew is installed on your mac

[![Build Status](https://travis-ci.org/osxc/homebrew.svg)](https://travis-ci.org/osxc/homebrew/)

## Requirements

- XCode Command-Line Tools (needs `git`)

## Role variables

| Name                  | Description                                      | Default            |
|-----------------------|--------------------------------------------------|--------------------|
| `installation_method` | The way to install homebrew, `script` or `clone` | `script`           |
| `clone_dir`           | The path where homebrew will be cloned           | `~/src/github.com/Homebrew/homebrew` |
| `install_dir`         | The path where homebrew will be installed        | `/usr/local`       |

## Dependencies

none

## License

MIT

## Author

- Robin Ricard
