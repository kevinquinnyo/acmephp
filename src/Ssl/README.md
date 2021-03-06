Acme PHP SSL
============

> Note : this repository is in alpha stage but only to follow the same versionning as the CLI
> client. This library's API won't change in the near future (we don't want BC breaks now).

> This library is a part of the [Acme PHP initiative](https://github.com/acmephp/acmephp),
> aiming to intregrate [Let's Encrypt](https://letsencrypt.org)
> in the PHP world at the application level.

Acme PHP SSL is a PHP wrapper around OpenSSL extension providing SSL encoding,
decoding, parsing and signing features.

It uses the recommended security settings and let you interact in a OOP
manner with SSL entities (public/private keys, certificates, ...).

## Why use Acme PHP SSL?

Acme PHP SSL provides various useful tools solving different use-cases:
- generate public and private keys (see the `Generator\KeyPairGenerator`) ;
- sign data using a private key (see `Signer\DataSigner`) ;
- parse certificates to extract informations about them (see `Parser\CertificateParser`) ;

There are many more possible use-cases, don't hesitate to dig a bit deeper in the
documentation to find out if this library can solve your problem!

## Documentation

Read the official [Acme PHP SSL documentation](https://acmephp.github.io/acmephp/ssl/introduction.html).
