---
title: "authelia crypto pair ecdsa"
description: "Reference for the authelia crypto pair ecdsa command."
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

## authelia crypto pair ecdsa

Perform ECDSA key pair cryptographic operations

### Synopsis

Perform ECDSA key pair cryptographic operations.

This subcommand allows preforming ECDSA key pair cryptographic tasks.

```
authelia crypto pair ecdsa [flags]
```

### Examples

```
authelia crypto pair ecdsa --help
```

### Options

```
  -h, --help   help for ecdsa
```

### Options inherited from parent commands

```
  -c, --config strings                        configuration files or directories to load (default [configuration.yml])
      --config.experimental.filters strings   list of filters to apply to all configuration files, for more information: authelia --help authelia filters
```

### SEE ALSO

* [authelia crypto pair](authelia_crypto_pair.md)	 - Perform key pair cryptographic operations
* [authelia crypto pair ecdsa generate](authelia_crypto_pair_ecdsa_generate.md)	 - Generate a cryptographic ECDSA key pair

