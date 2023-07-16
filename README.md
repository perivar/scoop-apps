# Per Ivar`s Scoop Bucket

[![Tests](https://github.com/perivar/scoop-apps/actions/workflows/ci.yml/badge.svg)](https://github.com/perivar/scoop-apps/actions/workflows/ci.yml) [![Excavator](https://github.com/perivar/scoop-apps/actions/workflows/excavator.yml/badge.svg)](https://github.com/perivar/scoop-apps/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add scoop-apps https://github.com/perivar/scoop-apps`. To install, do `scoop install <manifest>`.

To check that this bucket works after adding it, you can do the following:

`scoop bucket list` -> you should see 'scoop-apps'

`scoop search wavosaur` -> you should see wavosaur listed under, 'scoop-apps bucket:'

`scoop install wavosaur`

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----

#### To use this template

- Modify the Readme.md and the bin/auto-pr.ps1 files accordingly.
- Enable GitHub Actions for this repository.
