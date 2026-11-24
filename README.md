# sweet-saver-fare-tools
Official Sweet Saver Fare CLI and AI integration distributions

## Install the CLI

Use Node.js 22 or newer. Install the package attached to the 0.2.0 release, then check the installed version.

```sh
npm install --global https://github.com/ptse8204/sweet-saver-fare-tools/releases/download/ssf-tools-v0.2.0/sweet-saver-fare-0.2.0.tgz
ssf --version
```

The same command upgrades an existing 0.1.0 installation. To list ferry routes and read the saved Tsawwassen to Swartz Bay timetable, run these commands without signing in.

```sh
ssf schedules routes --json
ssf schedules show --route TSA_SWB --json
```

Confirm departure times with BC Ferries before travelling. The [release page](https://github.com/ptse8204/sweet-saver-fare-tools/releases/tag/ssf-tools-v0.2.0) includes the CLI package and its SHA-256 checksum. Future versions appear in [Releases](https://github.com/ptse8204/sweet-saver-fare-tools/releases).
