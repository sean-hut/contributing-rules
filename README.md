# Contributing Rules

This project provides modular contributing rules for reuse by other projects.

## Example Use

Here are some examples of projects selectively referencing these
contributing rules.

- [this project][this-project]
- [Eping][eping]
- [Amaranth Commit Message Format][amaranth]
- [Amaranth Commit Message Git Hook][amaranth-hook]

[this-project]: <https://github.com/sean-hut/contributing-rules>
[eping]: <https://github.com/sean-hut/eping>
[amaranth]: <https://github.com/sean-hut/amaranth-commit-message-format>
[amaranth-hook]: <https://github.com/sean-hut/amaranth-commit-msg-hook>

## Rule Modules

Here are the different rule modules in different categories.

### Contributing Prerequisites

- [GPG2 Elliptic-Curve Signing Key][signing-key]
- [Provide GPG2 Public Key][public-key]
- [Contributor Agreement][agreement]
- Git Configuration Options:
    - [Git Configuration][git-config]
        Standard git configuration.
    - [Git Configuration][git-config-gpg-signoff]
        Git configuration with gpg2 signing and sign off.
- Git Hook Options:
    - [Git `pre-commit` Hook][pre-commit]
    - [Amaranth Git `commit-msg` Hook][commit-msg]

### Preparation for Commits

- [git-flow Branching][git-flow]
- [Fetch and Merge Before Committing][fetch-merge]
- [Update Documentation][docs]
- [Update Tests][tests]
- [Run Make][run-make]

### Committing

- [Small Commits][small-commits]
- [Sign Your Commits][sign-commits]
- Commit Message Formats:
    - [Amaranth Commit Message Format][amaranth]
    - [tpope Commit Message Format][tpope]

[signing-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/gpg2-eliptic-curve-signing-key.md>
[public-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/gpg2-public-key.md>
[agreement]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/contributor-agreement.md>
[git-config]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/git-configuration/git-configuration.md>
[git-config-gpg-signoff]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/git-configuration/git-configuration-gpg-signoff.md>
[pre-commit]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/git-hook/pre-commit.md>
[commit-msg]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/contributing-prerequisites/git-hook/commit-msg.md>

[git-flow]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/preparation-for-commits/git-flow-branching.md>
[fetch-merge]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/preparation-for-commits/fetch-and-merge-before-committing.md>
[docs]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/preparation-for-commits/update-documentation.md>
[tests]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/preparation-for-commits/update-tests.md>
[run-make]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/preparation-for-commits/run-make.md>

[small-commits]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/committing/small-commits.md>
[sign-commits]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/committing/sign-and-signoff-commits.md>
[amaranth]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/committing/commit-message-format/amaranth-commit-message-format.md>
[tpope]: <https://github.com/sean-hut/contributing-rules/blob/develop/rules/committing/commit-message-format/tpope-commit-message-format.md>

## Reference Material

Reference material is available for rules to link to.

- [Creating a GPG2 Elliptic-Curve Signing Key][create-key]
- [Lookup GPG2 Key Id for Git][key-id-for-git]
- [Lookup GPG2 Elliptic-Curve Fingerprint][fingerprint]
- [What To Enter For `<your-name>`][name]

[create-key]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/creating-gpg2-eliptic-curve-signing.md>
[key-id-for-git]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/gpg2-key-id-for-git.md>
[fingerprint]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/lookup-fingerprint.md>
[name]: <https://github.com/sean-hut/contributing-rules/blob/develop/reference/your-name-value.md>

## License

The license file is: `LICENSE`

This project is licensed under the BSD Zero Clause License (SPDX: 0BSD).

Links for more information on the license:

- [License Commentary][landley]
- [SPDX][spdx]
- [Open Source Initiative][osi]

[landley]: <https://web.archive.org/web/20200909121328/https://landley.net/toybox/license.html>
[spdx]: <https://web.archive.org/web/20200909121345/https://spdx.org/licenses/0BSD.html>
[osi]: <https://web.archive.org/web/20200923194052/https://opensource.org/licenses/0BSD>

## Changelog

The changelog file is: CHANGELOG.md

All notable changes to this project are documented in the changelog file.

## Versions

### Development Version

The development version is at the head of the `develop` branch.

### Stable Versions

The current stable release is `0.3.0`.

Stable releases are tagged on the `releases` branch.

The [SemVar][semvar] version of semantic versioning is used.

[semvar]: <https://web.archive.org/web/20201009135328/https://semver.org/>

## Contributing

Contributions are welcome and appreciated.

These are the [contributing rules][rules].

[rules]: <https://github.com/sean-hut/contributing-rules/tree/develop/CONTRIBUTING/CONTRIBUTING.md>
