# OpenTurtle OS Desktop Releases

This public repository contains only desktop installer artifacts and auto-update feed files.

OpenTurtle OS source code is not published here.

## Workflows

- `desktop-release.yml` builds and publishes full signed desktop installers.
- `desktop-renderer-release.yml` publishes renderer-only resource updates by uploading only
  `OpenTurtle.OS-renderer-<version>.zip`, `renderer-update.json`, and the versioned renderer manifest.
