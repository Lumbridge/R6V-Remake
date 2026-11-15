# Rainbow Six Vegas UE5 Remake

Windows launcher and development-preview downloads for the Rainbow Six Vegas remake in Unreal Engine 5.8.

## Install and play

1. Open [the latest release](https://github.com/Lumbridge/R6V-Remake/releases/latest) and download **R6V.Launcher.exe**.
2. Run the launcher and choose **INSTALL**.
3. Choose **PLAY** when installation finishes.

Unreal Editor and a separate .NET installation are not required. The launcher verifies game downloads, installs future game updates and keeps the previous build if an installation fails or is cancelled. Game settings and saves are kept separately from installed releases.

## Development preview

Current development routes include solo/cooperative Terrorist Hunt on Kill House and LVU Campus, plus Team Sharpshooter, Team Survival, Sharpshooter and Survival on Kill House. The complete original campaign, modes/maps, gameplay fidelity and broader multiplayer acceptance remain in development. Read each release's notes for its actual scope.

## Updates and troubleshooting

The launcher checks for new game releases automatically. **Check for updates** runs a manual check; **Play current build** can defer an available update. The standalone EXE includes the official release-feed address, so no companion configuration file is needed.

**Settings** selects an existing packaged game or, under Development settings, a local project/engine installation. **Game folder** opens the active build. Launcher settings and logs are under `%LOCALAPPDATA%/R6VRemake/Launcher`; game saves are managed by Unreal separately. Launcher updates themselves are downloaded from this release page.

The game and launcher have independent version numbers. This repository hosts release downloads rather than the development source checkout.