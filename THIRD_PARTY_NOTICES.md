# Third-party notices

This application includes modified bundles from [oyc0401/maple-auction-mcp](https://github.com/oyc0401/maple-auction-mcp), Copyright (c) 2026 oyc0401, under the MIT License. Complete notices are included in `vendor/auction-mcp/LICENSE` and `vendor/chrome-extension/LICENSE`. Original bundle hashes, upstream revisions and local changes are recorded in `vendor/PROVENANCE.json`.

Electron, Chromium, Node.js and electron-builder dependencies retain their own licenses. Electron's generated LICENSE and LICENSES.chromium.html must remain in the packaged distribution. Build-tool dependencies are development-only.

The application does not include a NEXON API key, user session, cookie, account record, or developer market snapshot. Desktop auction access uses the end user's dedicated Electron browser session through an app-owned IPC transport; personal web mode still supports a Chrome companion extension. This fan application is not affiliated with NEXON.

The Windows desktop app includes electron-updater 6.8.11 (MIT) and its runtime dependencies for update delivery. Their licenses remain within the bundled dependency packages. Update metadata and installers are served from the public 9root3/maple-mvp-releases repository; the source development repository remains private.
