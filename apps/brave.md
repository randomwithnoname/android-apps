Brave for Android is a Chromium-based browser. It includes it's own content blocker ("Brave Shields") which is essentially a Rust version of uBlock Origin. It's not particularly focused on security and does add a lot of unnecessary features (attack surface) such as a cryptocurrency wallet and their scheme to try and replace ads. 

Brave [uses](https://github.com/brave/brave-core/pull/18543) the anti-competitive Play Integrity API to make certain features exclusive to Google certified operating systems. They don't provide official support for using it without Google Play even though Chromium does with certain features missing. They could use the hardware attestation API instead to provide support for more than Google certified operating systems:

[grapheneos.org/articles/atte…](https://grapheneos.org/articles/attestation-compatibility-guide)

GrapheneOS unsuccessfully tried to convince them to officially support not having Google Play without success so they didn't ask about this.

Despite this, Brave remains the best option for GrapheneOS users when Vanadium doesn't meet their needs (doesn't currently have as good content filtering as Brave). Brave is far from perfect but certainly much less bad than most other options, especially the Gecko-based ones (Firefox, etc.).
### Brave
- [x] [Google Play](https://play.google.com/store/apps/details?id=com.brave.browser)
- [x] [GitHub](https://github.com/brave/brave-browser)
- [x] [Official site](https://brave.com/)
