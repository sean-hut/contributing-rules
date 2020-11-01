# Changelog

All notable changes to this project are documented in this file.

## Changelog Format

This changelog format is based on [Keep a Changelog][changelog].

[changelog]: <https://web.archive.org/web/20201014163139/https://keepachangelog.com/en/1.0.0/>

## Semantic Versioning

This project adheres to the [SemVar][semvar] version of semantic
versioning.

[semvar]: <https://web.archive.org/web/20201009135328/https://semver.org/>

## Date Format

This project uses the [ISO 8601 date format][iso] of (YYYY-MM-DD).

[iso]: <https://web.archive.org/web/20201012024406/https://www.iso.org/iso-8601-date-and-time-format.html>

## [Unreleased]

## [0.3.0] - 2020-10-31

### Added

- Contributing Rule Modules:
    - Contributing Prerequisites:
        - Git Hook Options:
            - Git pre-commit Hook to run make
            - Git commit-msg Hook
                Checks conformance with the Amaranth commit message format.

### Changed

- Moved the [Amaranth Commit Message Format][amaranth] to it's own repository

[amaranth]: <https://github.com/sean-hut/amaranth-commit-message-format>

## [0.2.0] - 2020-10-21

### Added

- Contributing Rule Modules:
    - Committing:
        - Commit Message Formats:
            - Amaranth Commit Message Format:
                - Add M (Merge) category abbreviation

### Changed
- Contributing Rule Modules:
    - Committing:
        - Commit Message Formats:
            - Amaranth Commit Message Format:
                - Reformat category abbreviations

### Fixed

- Contributing Rule Modules:
    - Contributing Prerequisites:
        - Contributor Agreement:
            - Fix broken links

## [0.1.0] - 2020-10-21

### Added

- BSD Zero Clause license (SPDX: 0BSD)
- Contributing Rule Modules:
    - Contributing Prerequisites:
        - GPG2 Elliptic-Curve Signing Key
        - Provide GPG2 Public Key
        - Contributor Agreement
        - Git Configuration Options:
            - Standard git configuration
            - Git configuration with gpg2 signing and sign off
    - Preparation for Commits:
        - git-flow Branching
        - Fetch and Merge Before Committing
        - Update Documentation
        - Update Tests
        - Run Make
    - Committing:
        - Small Commits
        - Sign Your Commits
        - Commit Message Formats:
            - Amaranth Commit Message Format
            - tpope Commit Message Format
- References:
    - Creating a GPG2 Elliptic-Curve Signing Key
    - Lookup GPG2 Key Id for Git
    - Lookup GPG2 Elliptic-Curve Fingerprint
    - What To Enter For `<your-name>`
- Readme
- Changelog
- Makefile
