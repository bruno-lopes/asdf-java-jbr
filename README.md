<div align="center">

# asdf-java-jbr [![Build](https://github.com/bruno-lopes/asdf-java-jbr/actions/workflows/build.yml/badge.svg)](https://github.com/bruno-lopes/asdf-java-jbr/actions/workflows/build.yml) [![Lint](https://github.com/bruno-lopes/asdf-java-jbr/actions/workflows/lint.yml/badge.svg)](https://github.com/bruno-lopes/asdf-java-jbr/actions/workflows/lint.yml)

[java-jbr](https://github.com/bruno-lopes/java-jbr) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add java-jbr
# or
asdf plugin add java-jbr https://github.com/bruno-lopes/asdf-java-jbr.git
```

java-jbr:

```shell
# Show all installable versions
asdf list-all java-jbr

# Install specific version
asdf install java-jbr latest

# Set a version globally (on your ~/.tool-versions file)
asdf global java-jbr latest

# Now java-jbr commands are available
java -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bruno-lopes/asdf-java-jbr/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bruno Lorenço Lopes](https://github.com/bruno-lopes/)
