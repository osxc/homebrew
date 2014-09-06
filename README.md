homebrew
========

Ensure that homebrew is installed on your mac

[![Build Status](https://travis-ci.org/osxc/homebrew.svg)](https://travis-ci.org/osxc/homebrew/)

## Requirements

- XCode Command-Line Tools (needs `git`)
- Needs root if you want to affect other users

## Role variables

| Name                  | Description                                      | Default            |
|-----------------------|--------------------------------------------------|--------------------|
| `installation_method` | The way to install homebrew, `script` or `clone` | `script`           |
| `clone_dir`           | The path where homebrew will be cloned           | `/Users/{{ ansible_user_id }}/src/github.com/Homebrew/homebrew` |
| `install_dir`         | The path where homebrew will be installed        | `/usr/local`       |
| `install_cask`        | Defines if you want to install Homebrew Cask too | `yes`              |
| `affected_users`      | The users affected by the custom settings        | `[ "{{ ansible_user_id }}" ]` |

## Dependencies

- `osxc.common-env`

## License

MIT

## Author

- Robin Ricard
