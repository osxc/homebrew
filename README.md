homebrew
========

Ensure that homebrew is installed on your mac

[![Build Status](https://travis-ci.org/osxc/homebrew.svg)](https://travis-ci.org/osxc/homebrew/)

## Requirements

ansible-playbook -K as sudo is required to maintain permissions

## Role variables

Default is:

```yaml
installation_method: script
clone_dir: ~/src/github.com/Homebrew/homebrew
install_dir: "/usr/local"
```

### Description

- `installation_method` - How to install homebrew ? By homebrew's `script` or by git `clone` ?
- `clone_dir` - Where to install homebrew (in case of `clone` installation) ?
- `install_dir` - Where to copy it's contents and symlink clone_dir to ?

## Dependencies

none

## License

MIT

## Author

- Robin Ricard
