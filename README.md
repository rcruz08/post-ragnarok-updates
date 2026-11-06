# Post-Ragnarök — Game Update Downloads

This is the **public downloads-only repository** for Post-Ragnarök.

- The actual game source remains in a **separate private repository**.
- Verified Windows game builds and the publisher-signed `update.json` manifest are distributed through **GitHub Releases**.
- The Post-Ragnarök Launcher reads the latest signed manifest at:
  `https://github.com/rcruz08/post-ragnarok-updates/releases/latest/download/update.json`
- Individual files are integrity-checked by SHA-256 and the manifest must verify against the public key pinned in the launcher.
- This repository is **not** the update signing key or game source location; never publish secrets or private keys here.

## Current availability

**Latest: [vG1.3](https://github.com/rcruz08/post-ragnarok-updates/releases/tag/vG1.3)** — approved Apprentice art integration and eight-direction sprite atlas, published with signed `update.json` following Godot tests and Microsoft Defender scanning. Previous [vG1.2](https://github.com/rcruz08/post-ragnarok-updates/releases/tag/vG1.2) is retained. The unchanged 97.5 MB engine EXE hashes identically between G1.2 and G1.3, so players with G1.2 installed should fetch just the changed 2.38 MB `.pck` when checking for updates.

**Security:** An antivirus scan does not guarantee software is risk-free or reverse a Chrome Safe Browsing block. Do not bypass browser or antivirus warnings to install a build. The Windows launcher and game executables are currently unsigned developer builds.
