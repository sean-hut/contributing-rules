# Amaranth Commit Message Format

## Summary

The summary line is the first line of the commit message.

- A commit message must have a summary line.
- The summary must not be more than 50 characters.
- The summary must not end with a period.
- The summary must start with one of the [category abbreviation](#category-abbreviation) for example `B`.
- The summary's first word after the category abbreviation must be lower case.
- The summary must use the imperative mood.  See [imperative mood](#imperative-mood).

## Separate the Summary and Body

Separate the summary and the body with a blank line.

## Body

The body explains what changed and the rational for why it changed.

- The body must use the imperative mood.  See [imperative mood](#imperative-mood).
- The body lines must wrap at 72 characters.
- The body can contain blank lines.
- The body can contain bullet points that start with `-` or `*`.

## Separate the Body and Body Footer

Separate the body and body footer with a blank line.

## Body Footer

The body can have an optional footer.  The body footer comes after the body.

The body footer refers to issue IDs for example:
- Resolves: `<issue-id>`
- See also: `<issue-id>`, `<issue-id>`

## Category Abbreviation

These category abbreviation are sorted alphabetically.

- **AA** (API Additions)

    Adding functionality to the API.  For example:

    - Adding user facing features
    - Adding user configurations

- **AR** (API Removals)

    Removing functionality from the API. For example:

    - Removing user facing features
    - Removing user configurations

- **B** (Build)

    Changes that effect the build tools.  For example:

    - Changes to the Makefile.

- **BF** (Bug Fix)

    Fixing an error in the source code.

- **C** (Configuration)

    Changes to configurations.  For example:

    - .gitignore

- **CT** (Contributing)

    Use this when the commit is for managing contributing requirements  For example:

    - Adding a gpg2 elliptic-curve signing key and fingerprint.
    - Signing a contributor agreement.
    - Setting up contributing directories.
    - Revoking a signing key and resigning with a new key.

- **D** (Documentation)

    Changes to documentation.  For example:

    - README.md
    - CHANGELOG.md
    - Texinfo file

- **DD** (Developer Dependencies)

    Changes to developer dependencies.  Developer dependencies are
    programs developers need to have installed.

- **IV** (Increment Version)

    Increment a version number.

- **M** (Merge)

    Merging a branch into another branch.

- **R** (Refactor)

    Changes that do not effect the API and do not add or remove features.

- **RD** (Runtime Dependencies)

    Changes to the projects runtime dependencies.  Runtime dependencies
    are programs the users need to have installed.

- **RV** (Revert)

    Reverting a commit.

- **T** (Test)

    Adding or changing tests.

## Imperative Mood

- Add not Added nor Adds
- Remove not Removed nor Removes
- Fix not Fixed nor Fixes
