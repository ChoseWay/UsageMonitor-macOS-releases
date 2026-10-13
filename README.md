# Usage Monitor macOS binary releases

This repository hosts macOS installation packages and signed Sparkle update feeds only. Application source and CI signing credentials are kept separately in a private repository.

Supported platform: Apple Silicon (M-series), macOS 13 or later.

Test releases use ad-hoc application signing and Ed25519-signed update archives/feeds. They are not Apple-notarized production releases. First installation may require explicit approval in macOS Privacy & Security.

- [Downloads](https://github.com/ChoseWay/UsageMonitor-macOS-releases/releases)
- Stable feed: `appcast.xml`
- Preview feed: `appcast-preview.xml`

0.7.3 has no configured update feed: install an update-enabled package manually once. Afterwards, use Check for Updates in the app. Updates preserve member settings outside the application bundle.
