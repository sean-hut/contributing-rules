# Creating a GPG2 Elliptic-Curve Signing Key

If you do not have any `gpg2` keys you can create an elliptic-curve
signing key by following these steps:

1. Install `gpg2`.

1. Create a key with `gpg2 --full-generate-key --expert`

1. When prompted with "Please select what kind of key you want:"
   select "ECC (sign only)" or "ECC and ECC".

   ECC stands for elliptical-curve cryptography.

1. Then when prompted with "Please select which elliptic curve you
   want:" select "Curve 25519".

   The selection of Curve 25519 is based on [SafeCurves][safecurves].

1. Complete the rest of the prompts.

# Creating a GPG2 Elliptic-Curve Signing Subkey

If you have a `gpg2` key you can create an elliptic-curve signing
subkey by following these steps:

1. Install `gpg2`.

1. Look up the finger print of your existing key with this command:

`gpg2 --show-keys --with-fingerprint`

"268F 448F CCD7 AF34 183E 52D8 9BDE 1A08 9E98 BC16" is an example of a
key fingerprint.

1. Create a sub key with `gpg2 --edit-key --expert "<fingerprint>"`
-- Where `<fingerprint>` is the fingerprint form the previous step.

1. At the prompt "gpg> " enter "addkey"

1. When prompted with "Please select what kind of key you want:"
   select "ECC (sign only)".

   ECC stands for elliptical-curve cryptography.

1. When prompted with "Please select which elliptic curve you want:"
   select "Curve 25519".

   The selection is based on [SafeCurves][safecurves].

1. Complete the rest of the prompts.

[safecurves]: <https://web.archive.org/web/20201001222830/https://safecurves.cr.yp.to/>

