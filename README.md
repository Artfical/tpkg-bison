# bison

GNU Bison 3.8.2, the parser generator

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install bison
```

| | |
|---|---|
| Version | 3.8.2 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`m4`](https://github.com/Artfical/tpkg-m4) |
| Needs tOS build | 619 or newer |
| Size | 467688 bytes (1367313 unpacked) |
| SHA-256 of the `.tpkg` | `7ae93883e533854a303a0babcd4d38567db7d6893eaec21ee208233393e0818f` |

## Commands it adds

| Command | Runs |
|---|---|
| `bison` | `bin/bison` |
| `yacc` | `bin/yacc` |

## Download

The package file (`bison-3.8.2.tpkg`) and the sources it was built from are the assets of the
[v3.8.2 release](https://github.com/Artfical/tpkg-bison/releases/tag/v3.8.2).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `bison-3.8.2.tar.xz`

Check a download: `sha256sum bison-3.8.2.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
