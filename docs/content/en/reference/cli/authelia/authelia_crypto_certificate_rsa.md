---
title: "authelia crypto certificate rsa"
description: "Reference for the authelia crypto certificate rsa command."
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

## authelia crypto certificate rsa

Perform RSA certificate cryptographic operations

### Synopsis

Perform RSA certificate cryptographic operations.

This subcommand allows preforming RSA certificate cryptographic tasks.

### Examples

```
authelia crypto certificate rsa --help
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

* [authelia crypto certificate](authelia_crypto_certificate.md)	 - Perform certificate cryptographic operations
* [authelia crypto certificate rsa generate](authelia_crypto_certificate_rsa_generate.md)	 - Generate an RSA private key and certificate
* [authelia crypto certificate rsa request](authelia_crypto_certificate_rsa_request.md)	 - Generate an RSA private key and certificate signing request

