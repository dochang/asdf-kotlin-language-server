# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test kotlin-language-server https://github.com/dochang/asdf-kotlin-language-server.git "kotlin-language-server --version"
```

Tests are automatically run in GitHub Actions on push and PR.
