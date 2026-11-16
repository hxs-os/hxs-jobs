# hxs-jobs

GitHub Actions workflows to build HxS images and tarballs.

## create an HxS standard tarball (`standard-tarball.yml`)

[![create an HxS standard tarball](https://github.com/juanvel4000/hxs-jobs/actions/workflows/standard-tarball.yml/badge.svg)](https://github.com/juanvel4000/hxs-jobs/actions/workflows/standard-tarball.yml)

- **HxS Version**: `26a3`
- **HxS Flavor**: `standard`, `gnu`, `suckless`, `minimal`, `suckless-minimal`
- **HxS Architecture**: `x86_64`

Creates a `.tar.zst` archive containing an `hxs.SET-26a3-x86_64` filesystem produced by `hxsbootstrap`.

## create an HxS recovery image (`recovery-iso.yml`)

[![create an HxS Recovery Image](https://github.com/juanvel4000/hxs-jobs/actions/workflows/recovery-iso.yml/badge.svg)](https://github.com/juanvel4000/hxs-jobs/actions/workflows/recovery-iso.yml)

- **HxS Version**: `26a3`
- **HxS Flavor**: `gnu`
- **HxS Architecture**: `x86_64`

_Subsets: `efi`_

Creates an ISO designed as a recovery environment.
