# Lookup GPG2 Key Id for Git

Look up the fingerprint of your elliptic-curve signing key with this command:

`gpg2 --show-keys --with-fingerprint`

An example of a key fingerprint is `268F 448F CCD7 AF34 183E 52D8 9BDE 1A08 9E98 BC16`.

So in this example the `<fingerprint-without-spaces>` would be
`268F448FCCD7AF34183E52D89BDE1A089E98BC16`.  We remove the spaces from
the fingerprint.
