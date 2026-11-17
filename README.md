# hxs-jobs

GitHub Actions workflows to build HxS images and tarballs.

## create an HxS standard tarball (`standard-tarball.yml`)

[![create an HxS standard tarball](https://github.com/hxs-os/hxs-jobs/actions/workflows/standard-tarball.yml/badge.svg)](https://github.com/hxs-os/hxs-jobs/actions/workflows/standard-tarball.yml)

- **HxS Version**: `26a3`
- **HxS Flavor**: `standard`, `gnu`, `suckless`, `minimal`, `suckless-minimal`
- **HxS Architecture**: `x86_64`

Creates a `.tar.zst` archive containing an `hxs.SET-26a3-x86_64` filesystem produced by `hxsbootstrap`.

## create an HxS live iso image (`live-iso.yml`)

[![create an HxS live iso image](https://github.com/hxs-os/hxs-jobs/actions/workflows/live-iso.yml/badge.svg)](https://github.com/hxs-os/hxs-jobs/actions/workflows/live-iso.yml)

- **HxS Version**: `26a3`
- **HxS Flavor**: `gnu`
- **HxS Architecture**: `x86_64`

_Subsets: `efi`_

Creates a Live bootable ISO image based on `hxs-gnu-26a3-x86_64`

## License

[0BSD](https://spdx.org/licenses/0BSD.html), see [LICENSE](LICENSE)
