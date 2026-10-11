# OMP Agent desktop releases

This public repository holds the release assets and the updater feed (`latest.json`) for the OMP Agent desktop app, which is built from `BaxterCooper/omp-agent` (bundle identifier `dev.baxter.pi-agent`; releases before 0.3.0 were published as Pi Agent). An installed app checks this feed on every launch and updates itself.

## Install

Download the installer for your platform from the [latest release](https://github.com/BaxterCooper/omp-agent-releases/releases/latest). GitHub shows each file's SHA-256 digest on the release page.

- **Windows x64:** run `OMP.Agent_<version>_x64-setup.exe`. It installs for the current user without administrator rights. The installer is unsigned, so SmartScreen may ask you to choose **More info → Run anyway**.
- **macOS Apple Silicon:** open `OMP.Agent_<version>_aarch64.dmg` and drag **OMP Agent** to Applications. The app is ad-hoc signed and not notarized, so the first launch is blocked. Open it through **System Settings → Privacy & Security → Open Anyway**.

Other platforms are not supported.
