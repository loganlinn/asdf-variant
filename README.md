<div align="center">

# asdf-variant ![Build](https://github.com/loganlinn/asdf-variant/workflows/Build/badge.svg) ![Lint](https://github.com/loganlinn/asdf-variant/workflows/Lint/badge.svg)

[variant](https://github.com/mumoshu/variant2) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add variant https://github.com/loganlinn/asdf-variant.git
```

Tool:

```shell
# Show all installable versions
asdf list-all variant

# Install specific version
asdf install variant latest

# Set a version globally (on your ~/.tool-versions file)
asdf global variant latest

# Now variant commands are available
variant --help
```

Check [asdf-vm/asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

# License

See [LICENSE](LICENSE) © [<Logan Linn>](https://github.com/loganlinn/)
