# kiss.sh

> Applies the Camus Method to Bash.

`kiss.sh` is the companion tool for applying the Camus Method to Bash.

It generates signing keys, signs Bash scripts and verifies their integrity and compliance with the Bash specification of the Camus Method.

## Features

* Generate signing key pairs.
* Sign Bash scripts.
* Verify signatures.
* Validate compliance with the Bash specification of the Camus Method.

## Installation

*Coming soon.*

## Usage

```sh
kiss.sh <command> [options] [<file>...]
```

### Commands

| Command | Description |
|---|---|
| `keygen [--key-dir <path>] [--days <n>]` | Generate Ed25519 key pair |
| `check <file>` | Check script compliance |
| `sign [options] <file>...` | Sign file(s) |
| `verify [options] <file>` | Verify signature(s) |
| `list-keys [--key-dir <path>]` | List available public keys |
| `version` | Show version |
| `help` | Show this help |

### Options

| Option | Description |
|---|---|
| `--key-dir <path>` | Key storage directory (default: `~/.config/camus`) |
| `--signatory <name>` | Signatory name (optional, prompts if absent) |
| `--pubkey <path>` | Use specific public key |

## Documentation

The Camus Method and the Bash specification are available at:

https://camus-project.github.io

## License

MIT
