<div align="center">

# asdf-grafana-grizzly [![Build](https://github.com/daveneeley/asdf-grafana-grizzly/actions/workflows/build.yml/badge.svg)](https://github.com/daveneeley/asdf-grafana-grizzly/actions/workflows/build.yml) [![Lint](https://github.com/daveneeley/asdf-grafana-grizzly/actions/workflows/lint.yml/badge.svg)](https://github.com/daveneeley/asdf-grafana-grizzly/actions/workflows/lint.yml)

[grafana-grizzly](https://grafana.github.io/grizzly/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add grafana-grizzly
# or
asdf plugin add grafana-grizzly https://github.com/daveneeley/asdf-grafana-grizzly.git
```

grafana-grizzly:

```shell
# Show all installable versions
asdf list-all grafana-grizzly

# Install specific version
asdf install grafana-grizzly latest

# Set a version globally (on your ~/.tool-versions file)
asdf global grafana-grizzly latest

# Now grafana-grizzly commands are available
grr version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/daveneeley/asdf-grafana-grizzly/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dave Neeley](https://github.com/daveneeley/)
