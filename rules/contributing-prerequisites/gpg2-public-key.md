# Provide GPG2 Public Key

All contributors must provide their `gpg2` elliptic-curve public key
and it's fingerprint.

[How to create a `gpg2` elliptic-curve signing key][create-key].

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>

## Provide GPG2 Public Key and Fingerprint

1. Export your `gpg2` elliptic-curve public key.

`gpg2 --output <your-name>-public-signing-key.gpg --armor --export <fingerprint>`

Where `<your-name>` is your name.  For example john-smith.

[How to lookup your `<fingerprint>>`.][fingerprint]

1. Put `<your-name>-public-key.gpg` in:

    `contributing/contributors/<your-name>/public-key/current/`.

    Where `<your-name>` is your name.  For example john-smith.

1. Put your key's `<fingerprint>` in the file:

    `contributing/contributors/<your-name>/public-key/current/fingerprint.txt`

    Where `<your-name>` is your name.  For example john-smith.

[How to lookup your `<fingerprint>>`.][fingerprint]

## Signing Key Revocation

If you need to revoke your signing key.

1. Rename `contributing/contributors/<your-name>/public-key/current/`
to `contributing/contributors/<your-name>/public-key/revoked-<YYYY>-<MM>-<DD>/`.

    Where `<YYYY>` is the year, `<MM>` is the month and `<DD>` is the day.

    Where `<your-name>` is your name.  For example john-smith.

1.  Repeat the steps in the [Provide GPG2 Public Key and Fingerprint][public-key] section.

[fingerprint]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/lookup-fingerprint.md>
[public-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/gpg2-public-key#provide-gpg2--public-key-and-fingerprint>
