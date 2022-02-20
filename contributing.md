# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test jless https://github.com/jc00ke/asdf-jless.git "jless --version"
```

Tests are automatically run in GitHub Actions on push and PR.
