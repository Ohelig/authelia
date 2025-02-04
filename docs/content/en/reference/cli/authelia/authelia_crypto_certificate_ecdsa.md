---
title: "authelia crypto certificate ecdsa"
description: "Reference for the authelia crypto certificate ecdsa command."
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

## authelia crypto certificate ecdsa

Perform ECDSA certificate cryptographic operations

### Synopsis

Perform ECDSA certificate cryptographic operations.

This subcommand allows preforming ECDSA certificate cryptographic tasks.

### Examples

```
authelia crypto certificate ecdsa --help
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

* [authelia crypto certificate](authelia_crypto_certificate.md)	 - Perform certificate cryptographic operations
* [authelia crypto certificate ecdsa generate](authelia_crypto_certificate_ecdsa_generate.md)	 - Generate an ECDSA private key and certificate
* [authelia crypto certificate ecdsa request](authelia_crypto_certificate_ecdsa_request.md)	 - Generate an ECDSA private key and certificate signing request

