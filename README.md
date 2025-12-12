# QuickSSM Releases

This repository contains version information and download links for QuickSSM updates.

## Current Version

See [version.json](version.json) for the latest version information.

## Release Process

1. Build new version with `./build-release.sh`
2. Create GitHub Release and upload DMG
3. Update `version.json` with new version and download URL
4. Commit and push changes

## Version File Format

```json
{
  "version": "1.5.1",
  "releaseDate": "2025-12-12",
  "downloadUrl": "https://github.com/enzopellegrino/quickssm-releases/releases/download/vX.X.X/QuickSSM-X.X.X-arm64.dmg",
  "releaseNotes": [
    "Feature 1",
    "Feature 2"
  ]
}
```

## Auto-Update System

The QuickSSM app automatically checks this repository for updates at startup.
- Users can download updates without a license
- A valid license is required to use the app
