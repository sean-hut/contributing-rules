# Provide GPG2 Public Key

All contributors must provide their `gpg2` elliptic-curve public key
and it's fingerprint.

[How to create a `gpg2` elliptic-curve signing key][create-key].

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>

## Provide GPG2 Public Key and Fingerprint

1. Export your `gpg2` elliptic-curve public key.

    `gpg2 --output <your-name>-public-signing-key.gpg --armor --export <fingerprint>`

    [What To Enter For `<your-name>`][name].

    [How to lookup your `<fingerprint>>`.][fingerprint]

1. Put `<your-name>-public-key.gpg` in:

    `CONTRIBUTING/contributors/<your-name>/public-key/current/`.

    [What To Enter For `<your-name>`][name].

1. Put your key's `<fingerprint>` in the file:

    `CONTRIBUTING/contributors/<your-name>/public-key/current/fingerprint.txt`

    [What To Enter For `<your-name>`][name].

    [How to lookup your `<fingerprint>>`.][fingerprint]

## Signing Key Revocation

If you need to revoke your signing key.

1. Rename `CONTRIBUTING/contributors/<your-name>/public-key/current/`
to `CONTRIBUTING/contributors/<your-name>/public-key/revoked-<YYYY>-<MM>-<DD>/`.

    Where `<YYYY>` is the year, `<MM>` is the month and `<DD>` is the day.

    [What To Enter For `<your-name>`][name].

1.  Repeat the steps in the [Provide GPG2 Public Key and Fingerprint](#provide-gpg2-public-key-and-fingerprint) section.

[fingerprint]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/lookup-fingerprint.md>
[name]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/your-name-value.md>
