# Klay Releases

Official Windows installers for [Klay](https://klaysculpt.com). Each version is a
[GitHub Release](https://github.com/c6ank/klay-releases/releases) with its
`Klay_Setup_<version>.exe` attached.

- **Download:** https://klaysculpt.com/#get
- **Release notes:** `https://klaysculpt.com/releases/<version>`

`latest.json` is the signed update manifest. klaysculpt.com serves it at
`/update/latest.json`, and both the website's Download button and Klay's in-app update check
read it. `releases.json` lists every published version.

These files are written by `tools/release/klay_publish.py` in the Klay source repo. Don't
edit them by hand: an edit breaks the signature, and the app will ignore the manifest.
