<div align="center">

# asdf-roswell [![Build](https://github.com/troydm/asdf-roswell/actions/workflows/build.yml/badge.svg)](https://github.com/troydm/asdf-roswell/actions/workflows/build.yml) [![Lint](https://github.com/troydm/asdf-roswell/actions/workflows/lint.yml/badge.svg)](https://github.com/troydm/asdf-roswell/actions/workflows/lint.yml)

[roswell](https://roswell.github.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `git`, `autoconf`, `automake`, `make`, `cc` or `gcc` and `curl` headers, for more information see [Building from Source](https://roswell.github.io/Installation.html)

# Install

Plugin:

```shell
asdf plugin add roswell
# or
asdf plugin add roswell https://github.com/troydm/asdf-roswell.git
```

roswell:

```shell
# Show all installable versions
asdf list-all roswell

# Install specific version
asdf install roswell latest

# Set a version globally (on your ~/.tool-versions file)
asdf global roswell latest

# Now roswell commands are available
ros --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/troydm/asdf-roswell/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dmitry Geurkov](https://github.com/troydm/)
