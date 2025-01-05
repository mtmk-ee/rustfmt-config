# rustfmt-config

A nice little config for rustfmt.

## Setup

1. If you haven't already, `rustup toolchain install nightly`
2. Copy `rustfmt.toml` to your crate and/or clone this repository into your global rustfmt configuration folder:

| Platform | Path                                 |
| -------- | ------------------------------------ |
| Linux    | Usually `~/.config/`                 |
| macOS    | `$HOME/Library/Application Support/` |
| Windows  | `%APPDATA%\`                         |

3. Add `+nightly` to rust-analyzer's `rustfmt.extraArgs`
