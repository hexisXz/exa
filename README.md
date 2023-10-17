
<div align="center">


# exar

exa reborn. i might not do anything with this but i forked it because exa is dead.


### Manual installation from GitHub

Compiled binary versions of exa are uploaded to GitHub when a release is made.
You can install exa manually by [downloading a release](https://github.com/ogham/exa/releases), extracting it, and copying the binary to a directory in your `$PATH`, such as `/usr/local/bin`.

For more information, see the [Manual Installation page](https://the.exa.website/install/linux#manual).

### Cargo

If you already have a Rust environment set up, you can use the `cargo install` command:

    cargo install exa

Cargo will build the `exa` binary and place it in `$HOME/.cargo`.

To build without Git support, run `cargo install --no-default-features exa` is also available, if the requisite dependencies are not installed.


---
