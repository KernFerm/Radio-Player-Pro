## v0.0.45
- Dependency update

## v0.0.40
- Dependency update

## v0.0.32

### Added
- Native application Help menu entries for About, What's New, in-app Help, and Discord
- Safe native menu action bridge between the Electron main process and renderer
- Persistent system tray initialization at app startup
- Real Windows tray icon loading from packaged icon resources

### Fixed
- Default Electron Help menu items showing in production builds
- Developer tools exposure in the production application menu
- Missing tray icon visibility caused by creating the tray only during minimize
- Documentation version mismatch after the package version update

### Improved
- GitHub-facing project documentation with clearer setup, packaging, and feature details
- Production desktop experience consistency across the app menu, Help entry points, and tray behavior

## v0.0.30

### Added
- Live Radio Browser search by station name, tag, country, and language
- Infinite scrolling for global search results
- Global country and language lists loaded from dedicated upstream endpoints
- Windows `pack` and `dist:win` packaging scripts
- Assisted NSIS installer flow with install directory selection
- Installer license page using `build/LICENSE.txt`
- Custom NSIS uninstall cleanup script for Radio Player Pro data and cache folders
- Combined Windows application icon at `build/icon.ico`

### Fixed
- Minimize behavior no longer depends on tray-only restore
- Insights navigation now scrolls the internal main content panel correctly
- Country and language dropdown option visibility on Windows
- Electron Builder configuration issues blocking Windows packaging
- Invalid package script and dependency placement for Electron packaging

### Improved
- Version metadata and packaging configuration consistency
- Installer shortcut behavior for desktop and Start menu creation
- Windows icon handling for the packaged executable and shortcuts
- Documentation accuracy for the current application state
