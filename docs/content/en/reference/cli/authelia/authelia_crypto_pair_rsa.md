---
title: "authelia crypto pair rsa"
description: "Reference for the authelia crypto pair rsa command."
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

## authelia crypto pair rsa

Perform RSA key pair cryptographic operations

### Synopsis

Perform RSA key pair cryptographic operations.

This subcommand allows preforming RSA key pair cryptographic tasks.

```
authelia crypto pair rsa [flags]
```

### Examples

```
authelia crypto pair rsa --help
```

### Options

```
  -h, --help   help for rsa
```

### Options inherited from parent commands

```
  -c, --config strings                        configuration files or directories to load (default [configuration.yml])
      --config.experimental.filters strings   list of filters to apply to all configuration files, for more information: authelia --help authelia filters
```

### SEE ALSO

* [authelia crypto pair](authelia_crypto_pair.md)	 - Perform key pair cryptographic operations
* [authelia crypto pair rsa generate](authelia_crypto_pair_rsa_generate.md)	 - Generate a cryptographic RSA key pair

