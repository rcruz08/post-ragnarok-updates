# Post-Ragnarök — Game Update Downloads

This is the **public downloads-only repository** for Post-Ragnarök.

- The actual game source remains in a **separate private repository**.
- Verified Windows game builds and the publisher-signed `update.json` manifest are distributed through **GitHub Releases**.
- The Post-Ragnarök Launcher reads the latest signed manifest at:
  `https://github.com/rcruz08/post-ragnarok-updates/releases/latest/download/update.json`
- Individual files are integrity-checked by SHA-256 and the manifest must verify against the public key pinned in the launcher.
- This repository is **not** the update signing key or game source location; never publish secrets or private keys here.

## Current availability

Game releases are made **only after** the build, Godot tests, Windows Defender scan, integrity checks, and authorized manifest signing have passed. The launcher will report *No signed release published yet* until the first verified release is published.

**Security:** An antivirus scan does not guarantee software is risk-free or reverse a Chrome Safe Browsing block. Do not bypass browser or antivirus warnings to install a build. The Windows launcher and game executables are currently unsigned developer builds.
