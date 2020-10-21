# Contributor Agreement

All contributors must sign the Contributor Agreement with a `gpg2`
elliptic-curve signing key.

[How to create a `gpg2` elliptic-curve signing key][create-key].

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>

## Signing the Contributor Agreement

The Contributor Agreement file is
`contributing/contributor-agreement.txt`.

1. Create the directory `contributing/contributors/<your-name>/contributor-agreement/current/`.

    Where `<your-name>` is your name.  For example john-smith.

1. Copy `contributing/contributor-agreement.txt` to `contributing/contributors/<your-name>/contributor-agreement/current/contributor-agreement.txt`.

1. Sign `contributing/contributors/<your-name>/contributor-agreement/current/contributor-agreement.txt` with this command:

    `gpg2 --sign --detach-sign --default-key "<fingerpint>" contributor-agreement.txt`.

    [How to lookup your `<fingerprint>>`.][fingerprint]

    This will create the detached signature `contributing/contributors/<your-name>/contributor-agreement/current/contributor-agreement.txt.sig`.

## Signing Key Revocation

If you need to revoke your signing key.

1. Rename `contributing/contributors/<your-name>/contributor-agreement/current/`
to `contributing/contributors/<your-name>/contributor-agreement/revoked-<YYYY>-<MM>-<DD>/`.

    Where `<YYYY>` is the year, `<MM>` is the month and `<DD>` is the day.

    Where `<your-name>` is your name.  For example john-smith.

1.  Repeat the steps in the [Signing the Contributor Agreement][sign] section.

[fingerprint]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/lookup-fingerprint.md>
[sign]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/contributor-agreement#signing-the-contributor-agreement>
