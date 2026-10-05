# Trail Camera Wildlife Sorter: downloads

Windows installers for **Trail Camera Wildlife Sorter**, an offline-first app that sorts trail-camera
photos on your own computer. Photos are never uploaded.

**Official page: https://darrell-harris.com/software/**. Please start there; it explains the two
editions (a small download that fetches its models on first use, and a larger fully offline one).

The installers on the [Releases](../../releases) page are the same files that page links to.

## Verify your download

The installers are **not digitally signed** yet, so Windows SmartScreen may warn about an unknown publisher.
Each release lists a SHA-256 checksum for every installer. To check a download in PowerShell:

```powershell
Get-FileHash .\Trail-Camera-Wildlife-Sorter-Setup-<version>.exe -Algorithm SHA256
```

The value must match the one in the release notes and on https://darrell-harris.com/software/.
