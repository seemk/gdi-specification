# Repository

Every GDI project repository MUST adhere to the following specification before
it can release a `1.0.0` version.

## Required Files

- MUST have a `CHANGELOG.md` updated for every release
- MUST add the [CODE_OF_CONDUCT.md](templates/CODE_OF_CONDUCT.md)
- MUST add the [CONTRIBUTING.md](templates/CONTRIBUTING.md)
- MUST have a `.github/CODEOWNERS` file with at least two currently full-time Splunkers listed
  - MUST NOT have any non-full-time Splunkers listed in `.github/CODEOWNERS`
- MUST have an Apache 2.0 `LICENSE` file
- SHOULD have a `MIGRATING.md` if applicable
- MUST have a `README.md`
  - MUST have badges on `README.md` with code coverage and build status
  - SHOULD have badges on `README.md` for other relevant things including artifacts
  - MUST have getting started information in `README.md`
  - MUST have troubleshooting information in `README.md`
  - MUST have license information in `README.md`
- MUST have a `RELEASE.md` documenting the release process
- MUST add the [SECURITY.md](templates/SECURITY.md)
- SHOULD add dependabot information to SECURITY.md if applicable

## Required Configuration

- MUST have a primary branch named `main`
- MUST NOT allow pushing direct to `main`
- MUST require at least one CODEOWNER to approve a PR prior to merge
- MUST have dependabot properly configured

## Collector

- MUST document all supported configuration parameters
- MUST document sizing guidelines for all signals

## Instrumentation Libraries

- MUST document all supported configuration parameters
- MUST document how to configure manual instrumentation
- MUST document how to configure log correlation