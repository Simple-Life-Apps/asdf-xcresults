<div align="center">

# asdf-xcresults [![Build](https://github.com/voidless/asdf-xcresults/actions/workflows/build.yml/badge.svg)](https://github.com/voidless/asdf-xcresults/actions/workflows/build.yml) [![Lint](https://github.com/voidless/asdf-xcresults/actions/workflows/lint.yml/badge.svg)](https://github.com/voidless/asdf-xcresults/actions/workflows/lint.yml)

[xcresults](https://github.com/Simple-Life-Apps/xcresults) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add xcresults
# or
asdf plugin add xcresults https://github.com/voidless/asdf-xcresults.git
```

xcresults:

```shell
# Show all installable versions
asdf list-all xcresults

# Install specific version
asdf install xcresults latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcresults latest

# Now xcresults commands are available
xcresults --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/voidless/asdf-xcresults/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ilya Bersenev](https://github.com/voidless/)
