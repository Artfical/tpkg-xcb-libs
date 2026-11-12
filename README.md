# xcb-libs

The rest of libxcb: the extension libraries (render, shape, xfixes, sync, randr, xkb, xinput, glx...) and the xcb headers, for Qt and other X programs

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install xcb-libs
```

| | |
|---|---|
| Version | 1.17.0 |
| Licence | MIT |
| Upstream | https://xcb.freedesktop.org |
| Needs | [`xorg`](https://github.com/Artfical/tpkg-xorg) |
| Needs tOS build | 618 or newer |
| Size | 1017350 bytes (4797635 unpacked) |
| SHA-256 of the `.tpkg` | `c6f27c44c4a1a0da3fcd06e5998aded58dd302736102a376868b0740282be2ae` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`xcb-libs-1.17.0.tpkg`) and the sources it was built from are the assets of the
[v1.17.0 release](https://github.com/Artfical/tpkg-xcb-libs/releases/tag/v1.17.0).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `libxcb-1.17.0.tar.xz`

Check a download: `sha256sum xcb-libs-1.17.0.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
