<div align="center">

# asdf-mutagen [![Build](https://github.com/smaximoff/asdf-mutagen/actions/workflows/build.yml/badge.svg)](https://github.com/smaximoff/asdf-mutagen/actions/workflows/build.yml) [![Lint](https://github.com/smaximoff/asdf-mutagen/actions/workflows/lint.yml/badge.svg)](https://github.com/smaximoff/asdf-mutagen/actions/workflows/lint.yml)

[mutagen](https://mutagen.io/documentation/introduction) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add mutagen
# or
asdf plugin add mutagen https://github.com/smaximoff/asdf-mutagen.git
```

mutagen:

```shell
# Show all installable versions
asdf list-all mutagen

# Install specific version
asdf install mutagen latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mutagen latest

# Now mutagen commands are available
mutagen --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/smaximoff/asdf-mutagen/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sergii Maksymov](https://github.com/smaximoff/)
