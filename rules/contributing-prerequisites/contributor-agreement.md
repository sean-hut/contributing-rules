## Contributor Agreement

All contributors must sign the Contributor Agreement with a `gpg2` elliptic-curve signing key.

Instruction on how to create a `gpg2` elliptic-curve signing key.m

The Contributor Agreement file is
`contributing/contributor-agreement.txt`.

### Signing the Contributor Agreement

Signing the Contributor Agreement should be your first commit
contributed to this project.

1. Look up the fingerprint of your elliptic-curve signing key:

`gpg2 --show-keys --with-fingerprint`

As example of a key fingerprint is "268F 448F CCD7 AF34 183E 52D8 9BDE
1A08 9E98 BC16".

1. Sign contributor-agreement.txt

`gpg2 --sign --detach-sign --default-key "<fingerpint>" contributor-agreement.txt`.

Where `<fingerprint>` is the fingerprint from the previous step.

This will create a signed Contributor Agreement file named
`contributor-agreement.txt.sig`.

1. Create the directory `contributing/contributors/<YOUR_NAME>`.

   For example `contributing/contributors/john-smith`.

1. Put `contributor-agreement.txt` into your
   `contributing/contributors/<YOUR_NAME>` directory.

1. Put `contributor-agreement.txt.sig` into your
   `contributing/contributors/<YOUR_NAME>` directory.

1. Export your public key which others can use to verify your
   signatures.

`gpg2 --output <your-name>-public-signing-key.gpg --armor --export <fingerprint>`

-- Use your name where it says <your-name>.

-- Enter the fingerprint from the previous step where it says
`<fingerprint>`.

1. Put <your-name>-public-key.gpg in the
   `contributing/contributors/<YOUR_NAME>` directory.

1. Put the `<fingerprint>` from the previous step in the file
   `contributing/contributors/<YOUR_NAME>/fingerprint.txt`

### Signing Key Revocation

If you need to revoke your signing key move these files:

`contributing/contributors/<YOUR_NAME>/contributor-agreement.txt`
`contributing/contributors/<YOUR_NAME>/contributor-agreement.txt.sig`
`contributing/contributors/<YOUR_NAME>/<your-name>-public-signing-key.gpg`
`contributing/contributors/<YOUR_NAME>/fingerprint.txt`

To a new directory called
`contributing/contributors/<YOUR_NAME>/revoked-YYYY-MM-DD/`.  Where
YYYY is the year, MM is the month and DD is the day.

Then repeat the step in the "Signing the Contributor Agreement" section
above.
