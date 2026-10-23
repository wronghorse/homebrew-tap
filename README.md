# homebrew-tap

Homebrew formulae.

## Install

```sh
brew tap wronghorse/tap
brew trust wronghorse/tap
brew install helixx
```

Homebrew loads formulae from a third-party tap only after you trust it. To
trust one formula instead of the whole tap, install it with its full name, for
example `brew install wronghorse/tap/helixx`.

## Formulae

| Formula | Contents |
| --- | --- |
| `helixx` | Latest versioned helixx release. |
| `helixx-nightly` | helixx build of the latest `main` commit. |

Both helixx formulae support macOS on Apple Silicon and Linux on x86_64, and
install the `hx` executable. They conflict with each other and with the
Homebrew `helix` formula. Linux builds need glibc 2.39 or newer. Install
language servers separately.

`brew upgrade` follows each formula's channel. To switch channels, uninstall
one formula before you install the other.
