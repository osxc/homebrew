homebrew
========

Ensure that homebrew is installed on your mac

## Requirements

none

## Role variables

Default is:

```yaml
installation_method: script
clone_dir: ~/src/github.com/Homebrew/homebrew
```

### Description

- `installation_method` - How to install homebrew ? By homebrew's `script` or by git `clone` ?
- `clone_dir` - Where to install homebrew (in case of `clone` installation) ?

## Dependencies

none

## License

MIT

## Author

- Robin Ricard
