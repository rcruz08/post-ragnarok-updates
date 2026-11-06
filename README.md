# Post-Ragnarök — Game Update Downloads

This is the **public downloads-only repository** for Post-Ragnarök.

- The actual game source remains in a **separate private repository**.
- Verified Windows game builds and the publisher-signed `update.json` manifest are distributed through **GitHub Releases**.
- The Post-Ragnarök Launcher reads the latest signed manifest at:
  `https://github.com/rcruz08/post-ragnarok-updates/releases/latest/download/update.json`
- Individual files are integrity-checked by SHA-256 and the manifest must verify against the public key pinned in the launcher.
- This repository is **not** the update signing key or game source location; never publish secrets or private keys here.

## Current availability

**vG1.2 is now available:** [Post-Ragnarök G1.2 release](https://github.com/rcruz08/post-ragnarok-updates/releases/tag/vG1.2) has `Post-Ragnarok.exe`, `Post-Ragnarok.pck`, and publisher-signed `update.json`. The game was built from verified source and went through Godot regression tests and a Windows Defender scan. Use the latest launcher, which trusts the rotated publishing key.

**Security:** An antivirus scan does not guarantee software is risk-free or reverse a Chrome Safe Browsing block. Do not bypass browser or antivirus warnings to install a build. The Windows launcher and game executables are currently unsigned developer builds.
