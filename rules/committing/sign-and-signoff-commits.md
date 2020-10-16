# Sign and Signoff Your Commits

This project requires all commit are signed with a `gpg2`
elliptic-curve signature.

[How to create a `gpg2` elliptic-curve signing key][create-key].

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>

It also requires that commits have a sign off.

1. Look up the fingerprint of your elliptic-curve signing key:

`gpg2 --show-keys --with-fingerprint`

`268F 448F CCD7 AF34 183E 52D8 9BDE 1A08 9E98 BC16` is an example of a
key fingerprint.

1. Commit with `--signoff` and `--gpg-sign`

`git commit --signoff --gpg-sign=<fingerprint-without-spaces>`

For `<fingerprint-without-spaces>` use the fingerprint from the
previous step with out spaces.  So for example
`268F448FCCD7AF34183E52D89BDE1A089E98BC16`
