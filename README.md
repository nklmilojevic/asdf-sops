<div align="center">

# asdf-sops [![Build](https://github.com/nklmilojevic/asdf-sops/actions/workflows/build.yml/badge.svg)](https://github.com/nklmilojevic/asdf-sops/actions/workflows/build.yml) [![Lint](https://github.com/nklmilojevic/asdf-sops/actions/workflows/lint.yml/badge.svg)](https://github.com/nklmilojevic/asdf-sops/actions/workflows/lint.yml)


[sops](https://github.com/gosopsio/sops) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sops
# or
asdf plugin add sops https://github.com/nklmilojevic/asdf-sops.git
```

sops:

```shell
# Show all installable versions
asdf list-all sops

# Install specific version
asdf install sops latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sops latest

# Now sops commands are available
sops version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nklmilojevic/asdf-sops/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikola Milojević](https://github.com/nklmilojevic/)
