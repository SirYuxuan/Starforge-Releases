# Starforge

Official downloads and signed updates for Starforge, a native EVE Online desktop toolbox.
The application's source code is maintained in a separate private repository.

## Download

Open [Releases](https://github.com/SirYuxuan/Starforge-Releases/releases/latest)
and choose the archive for your platform:

- macOS Apple Silicon: `aarch64-apple-darwin`
- Windows 64-bit: `x86_64-pc-windows-msvc`

macOS: extract and move Starforge.app into Applications.
Windows: extract the entire Starforge folder before running Starforge.exe.
Do not copy only the executable: future bundles may include helpers, databases and resources.

## Updates

Settings > General > Software update checks this repository's stable Releases.
Updates are complete application bundles authenticated by an Ed25519-signed manifest.
Downloads are verified before installation. Installation requires your confirmation
and restarts the application. Personal data is stored outside the installation.

Versions predating 0.2.0 must be updated manually first.
Current macOS builds are ad-hoc signed, not notarized. Windows builds are not
publisher-signed. Update signatures are separate from operating-system code signing.

## Release assets

- Versioned application archives
- `latest.json`: signed update manifest
- `SHA256SUMS`: manual archive integrity checks

Only complete, published releases are offered by the updater.
