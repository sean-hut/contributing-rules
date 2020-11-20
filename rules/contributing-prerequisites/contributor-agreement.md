# Contributor Agreement

All contributors must sign the Contributor Agreement with a `gpg2`
elliptic-curve signing key.

[How to create a `gpg2` elliptic-curve signing key][create-key].

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>

## Signing the Contributor Agreement

The Contributor Agreement file is
`CONTRIBUTING/contributor-agreement.txt`.

1. Create the directory `CONTRIBUTING/contributors/<your-name>/contributor-agreement/current/`.

    [What To Enter For `<your-name>`][name].

1. Copy `CONTRIBUTING/contributor-agreement.txt` to `CONTRIBUTING/contributors/<your-name>/contributor-agreement/current/contributor-agreement.txt`.

1. Sign `CONTRIBUTING/contributors/<your-name>/contributor-agreement/current/contributor-agreement.txt` with this command:

    `gpg2 --sign --detach-sign --default-key "<fingerpint>" contributor-agreement.txt`.

    [How to lookup your `<fingerprint>>`.][fingerprint]

    This will create the detached signature `CONTRIBUTING/contributors/<your-name>/contributor-agreement/current/contributor-agreement.txt.sig`.

## Signing Key Revocation

If you need to revoke your signing key.

1. Rename `CONTRIBUTING/contributors/<your-name>/contributor-agreement/current/`
to `CONTRIBUTING/contributors/<your-name>/contributor-agreement/revoked-<YYYY>-<MM>-<DD>/`.

    Where `<YYYY>` is the year, `<MM>` is the month and `<DD>` is the day.

    [What To Enter For `<your-name>`][name].

1.  Repeat the steps in the [Signing the Contributor Agreement](#signing-the-contributor-agreement) section.

[fingerprint]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/lookup-fingerprint.md>
[name]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/your-name-value.md>
