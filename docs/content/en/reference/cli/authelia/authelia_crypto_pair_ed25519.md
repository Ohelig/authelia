---
title: "authelia crypto pair ed25519"
description: "Reference for the authelia crypto pair ed25519 command."
lead: ""
date: 2022-06-27T18:27:57+10:00
draft: false
images: []
menu:
  reference:
    parent: "cli-authelia"
weight: 905
toc: true
---

## authelia crypto pair ed25519

Perform Ed25519 key pair cryptographic operations

### Synopsis

Perform Ed25519 key pair cryptographic operations.

This subcommand allows preforming Ed25519 key pair cryptographic tasks.

```
authelia crypto pair ed25519 [flags]
```

### Examples

```
authelia crypto pair ed25519 --help
```

### Options

```
  -h, --help   help for ed25519
```

### Options inherited from parent commands

```
  -c, --config strings                        configuration files or directories to load (default [configuration.yml])
      --config.experimental.filters strings   list of filters to apply to all configuration files, for more information: authelia --help authelia filters
```

### SEE ALSO

* [authelia crypto pair](authelia_crypto_pair.md)	 - Perform key pair cryptographic operations
* [authelia crypto pair ed25519 generate](authelia_crypto_pair_ed25519_generate.md)	 - Generate a cryptographic Ed25519 key pair

