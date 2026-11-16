# hxs-jobs

GitHub Actions workflows to build HxS images and tarballs.

## create an HxS standard tarball (`standard-tarball.yml`)

[![create an HxS standard tarball](https://github.com/juanvel4000/hxs-jobs/actions/workflows/standard-tarball.yml/badge.svg)](https://github.com/juanvel4000/hxs-jobs/actions/workflows/standard-tarball.yml)

- **HxS Version**: `26a3`
- **HxS Flavor**: `standard`, `gnu`, `suckless`, `minimal`, `suckless-minimal`
- **HxS Architecture**: `x86_64`

Creates a `.tar.zst` archive containing an `hxs.SET-26a3-x86_64` filesystem produced by `hxsbootstrap`.
