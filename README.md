# kiss.sh

> Applies the Camus Method to Bash.

`kiss.sh` is the companion tool for applying [the Camus Method](https://camus-project.github.io/The-Camus-Method/) to Bash.

It generates signing keys, signs Bash scripts and verifies their integrity and compliance with [Camus.sh](https://camus-project.github.io/adaptations/Camus.sh/), the Bash specification of the Camus Method.

## Features

* Generate signing key pairs.
* Sign Bash scripts.
* Verify signatures.
* Validate compliance with Camus.sh.

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

## The Camus Project
kiss.sh is part of the [The Camus Project](https://camus-project.github.io):
> The Camus Project is a community effort to provide a method, specification language, programming language, and tooling for software where humans express intent, AI generates implementations, and humans assume responsibility for the resulting code.
> The project aims to make AI-generated software understandable, auditable, and certifiable.

## License

MIT

---
<pre>
*camus-sig-1*
**Signed -- Lan Jing**
Date: 2026-07-07T14:23:24Z
Fingerprint: SHA256:52:69:05:07:66:BD:DE:55:C7:D2:B1:52:9C:8F:ED:7B:05:E3:8E:57:7E:10:98:1E:7C:BD:13:96:85:4E:83:89
Signature: HoJbaCNMvpGSBRm/GzbSYbWREHIjagT1MLBp655BC8Q5GftXveiVaNMFVlYtTozqItFT9bLehehlepZToON4Dw==
</pre>
