<div align="center">

# asdf-arc [![Build](https://github.com/ORCID/asdf-arc/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-arc/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-arc/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-arc/actions/workflows/lint.yml)


[arc](https://github.com/goreleaser/arc) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add arc https://github.com/ORCID/asdf-arc.git
```

arc:

```shell
# Show all installable versions
asdf list-all arc

# Install specific version
asdf install arc latest

# Set a version globally (on your ~/.tool-versions file)
asdf global arc latest

# Now arc commands are available
arc --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

