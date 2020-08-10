# http4k Toolbox CLI

This repository stores the released binaries for the [http4k](https://http4k.org) CLI.

### Install via <a href="https://sdkman.io/">SDKman!</a>
SDKMan! provides package management for Unix-based systems.

To install SDKMan!, just paste the following into your terminal:
`curl -s https://get.sdkman.io | bash`

After installation, bootstrap SDKMan! by opening a new terminal:
`source "$HOME/.sdkman/bin/sdkman-init.sh"`

To install the latest http4k Toolbox binary:
`sdk install http4k`
... then test it with:
`http4k --version`

### Install via <a href="https://brew.sh//">Brew</a>
Brew is the "missing package manager for MacOS.

To install Brew, just paste the following into your terminal:
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

To install the latest http4k Toolbox binary:
`brew tap http4k/toolbox-cli && brew install http4k` 
... then test it with:
`http4k --version`
