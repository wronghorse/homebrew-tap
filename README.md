# homebrew-tap

Homebrew formulae.

## Install

```sh
brew install wronghorse/tap/helixx
```

## Formulae

| Formula | Contents |
| --- | --- |
| `helixx` | Latest versioned helixx release. |
| `helixx-nightly` | helixx build of the latest `main` commit. |

Both helixx formulae support macOS on Apple Silicon and Linux on x86_64, and
install the `hxx` executable. Linux builds need glibc 2.39 or newer. Install
language servers separately.

`brew upgrade` follows each formula's channel. To switch channels, uninstall
one formula before you install the other.
