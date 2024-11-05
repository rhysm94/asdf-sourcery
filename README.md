<div align="center">

# asdf-sourcery [![Build](https://github.com/rhysm94/asdf-sourcery/actions/workflows/build.yml/badge.svg)](https://github.com/rhysm94/asdf-sourcery/actions/workflows/build.yml) [![Lint](https://github.com/rhysm94/asdf-sourcery/actions/workflows/lint.yml/badge.svg)](https://github.com/rhysm94/asdf-sourcery/actions/workflows/lint.yml)

[sourcery](https://github.com/rhysm94/asdf-sourcery) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sourcery
# or
asdf plugin add sourcery https://github.com/rhysm94/asdf-sourcery.git
```

sourcery:

```shell
# Show all installable versions
asdf list-all sourcery

# Install specific version
asdf install sourcery latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sourcery latest

# Now sourcery commands are available
sourcery --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rhysm94/asdf-sourcery/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rhys Morgan](https://github.com/rhysm94/)
