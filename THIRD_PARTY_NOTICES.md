# Third-party components

CouchDeck's proprietary implementation and its separately licensed components
are not covered by a single license. Installing or sharing the product does
not change the licenses of those components.

The official 1.1.0 installation package includes:

- `licenses/THIRD_PARTY_NOTICES.md`: component attribution and upstream links.
- `licenses/THIRD_PARTY_LICENSES.txt` and individual license texts: applicable
  third-party terms, including GPL, LGPL, MIT, BSD and font licenses.
- `licenses/GPL-COMPONENT-SOURCES.md`: corresponding-source information for the
  exact distributed GPL component set.
- `licenses/sources/CouchDeck-GPL-Components-4cd799c95183cfa9.7z`: that component
  set's source and required build material.

## Corresponding source for version 1.1.0

[Download the matching GPL component source archive](https://github.com/CouchDeckApp/CouchDeck/releases/download/v1.1.0/CouchDeck-GPL-Components-4cd799c95183cfa9.7z).

SHA-256: `7df7cc2fa103a7adc9a572599042ed5d005ef6c80182f3c88257e8d0d7353759`

The archive includes the exact Apollo source and recursive submodules,
Moonlight Web Stream source and locked vendored dependencies, and the source
and build material for the GPL-covered Apollo console forwarder. Its
`SOURCE-MANIFEST.json` identifies the distributed component sources. It does
not contain CouchDeck's proprietary source code.

## Selected upstream projects

| Component | Project |
| --- | --- |
| Apollo | [ClassicOldSong/Apollo](https://github.com/ClassicOldSong/Apollo) |
| Sunshine, on which Apollo is based | [LizardByte/Sunshine](https://github.com/LizardByte/Sunshine) |
| Moonlight Web Stream | [MrCreativ3001/moonlight-web-stream](https://github.com/MrCreativ3001/moonlight-web-stream) |
| ViGEmBus | [nefarius/ViGEmBus](https://github.com/nefarius/ViGEmBus) |
| Wails | [wailsapp/wails](https://github.com/wailsapp/wails) |
| Microsoft WebView2 | [Microsoft WebView2 documentation](https://learn.microsoft.com/microsoft-edge/webview2/) |

This is navigation, not a replacement for the full notices and license texts
included with the product.
