<!-- markdownlint-disable MD041 -->
<div align="center">

# asdf-kotlin-language-server [![Build](https://github.com/dochang/asdf-kotlin-language-server/actions/workflows/build.yml/badge.svg)](https://github.com/dochang/asdf-kotlin-language-server/actions/workflows/build.yml) [![Lint](https://github.com/dochang/asdf-kotlin-language-server/actions/workflows/lint.yml/badge.svg)](https://github.com/dochang/asdf-kotlin-language-server/actions/workflows/lint.yml)


[kotlin-language-server](https://github.com/fwcd/kotlin-language-server#readme) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`: generic POSIX utilities.
- `ASDF_KOTLIN_LANGUAGE_SERVER_VERSION`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kotlin-language-server
# or
asdf plugin add kotlin-language-server https://github.com/dochang/asdf-kotlin-language-server.git
```

kotlin-language-server:

```shell
# Show all installable versions
asdf list-all kotlin-language-server

# Install specific version
asdf install kotlin-language-server latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kotlin-language-server latest

# Now kotlin-language-server commands are available
command -v kotlin-language-server
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dochang/asdf-kotlin-language-server/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Wade Zhang](https://github.com/dochang/)
