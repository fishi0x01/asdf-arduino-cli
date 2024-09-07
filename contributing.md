# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test arduino-cli https://github.com/fishi0x01/asdf-arduino-cli.git "arduino-cli version"
```

Tests are automatically run in GitHub Actions on push and PR.
