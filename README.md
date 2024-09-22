<div align="center">

# asdf-shellbits [![Build](https://github.com/mecha-hq/asdf-shellbits/actions/workflows/build.yml/badge.svg)](https://github.com/mecha-hq/asdf-shellbits/actions/workflows/build.yml) [![Lint](https://github.com/mecha-hq/asdf-shellbits/actions/workflows/lint.yml/badge.svg)](https://github.com/mecha-hq/asdf-shellbits/actions/workflows/lint.yml)

[shellbits](https://github.com/mecha-hq/shellbits) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add shellbits
# or
asdf plugin add shellbits https://github.com/mecha-hq/asdf-shellbits.git
```

shellbits:

```shell
# Show all installable versions
asdf list-all shellbits

# Install specific version
asdf install shellbits latest

# Set a version globally (on your ~/.tool-versions file)
asdf global shellbits latest

# Now shellbits scripts and makefiles are available
shellbits --help
```

Check [asdf](https://github.com/asdf-vm/asdf)'s or [mise](https://mise.jdx.dev)'s (preferred) readmes for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mecha-hq/asdf-shellbits/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mecha HQ](https://github.com/mecha-hq/)
