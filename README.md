Some scripts for rust development

### 1. Remote Cargo CLI

#### Description

**rcargo** is a command-line tool that allows you to build and install Rust binaries using cargo from a remote host and copy the binaries locally. It is useful for development and testing, especially when the local environment is not suitable for building the required binaries or if you want to build the binaries on remote workstation.

available commands:

- list: List the installed packages on the remote host.
- install: Install packages from crates.io with remote build.
<!-- - build: Remote build local cargo package. -->

### Contributing

If you have any suggestions or find any bugs, please feel free to open an issue or a pull request

### Todo:
* [ ] Installing binaries
    * [x] install a package binary from crates.io
    * [x] handle custom install parameters for cargo
    * [ ] install a cargo package bin from local path
* [ ] Building local project on remote machine
    * [ ] rsync local changes and build
    * [ ] add/exclude build artifacts from sync
