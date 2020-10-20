# Sign and Signoff Your Commits

This project requires all commit are signed with a `gpg2`
elliptic-curve signature.

[How to create a `gpg2` elliptic-curve signing key][create-key].

It also requires that commits have a sign off.

Use this git commit command when committing your changes:

`git commit --signoff --gpg-sign=<fingerprint-without-spaces>`

[Lookup your <fingerprint-without-spaces>.][key-id]

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>
[key-id]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/gpg2-key-id-for-git.md>
