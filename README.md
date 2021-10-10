<div align="center">

# asdf-slides [![Build](https://github.com/grimoh/asdf-slides/actions/workflows/build.yml/badge.svg)](https://github.com/grimoh/asdf-slides/actions/workflows/build.yml) [![Lint](https://github.com/grimoh/asdf-slides/actions/workflows/lint.yml/badge.svg)](https://github.com/grimoh/asdf-slides/actions/workflows/lint.yml)


[slides](https://github.com/maaslalani/slides) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add slides
# or
asdf plugin add slides https://github.com/grimoh/asdf-slides.git
```

slides:

```shell
# Show all installable versions
asdf list-all slides

# Install specific version
asdf install slides latest

# Set a version globally (on your ~/.tool-versions file)
asdf global slides latest

# Now slides commands are available
slides --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/grimoh/asdf-slides/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [grimoh](https://github.com/grimoh/)
