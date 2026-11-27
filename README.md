# Flight Deck – MSFS 2020 Checklists

A simulator-only checklist companion for the 20 aircraft in the original MSFS 2020 Standard Edition.

## Run in a browser
Download the repository ZIP, extract it, and open `index.html`.

## Windows desktop installer
Every push to `main` that changes the app files starts the **Build Windows Desktop App** workflow.

1. Open the repository's **Actions** tab.
2. Select the latest **Build Windows Desktop App** run.
3. When it finishes successfully, open the run and download the **Flight-Deck-Windows-Installer** artifact.
4. Extract the downloaded ZIP and run the `.exe` installer.

The installer is built by GitHub Actions; it is not committed to the source repository.

## Install as a browser app (optional)
The repository also includes a web app manifest and offline service worker. After enabling GitHub Pages with **Settings → Pages → Build and deployment → GitHub Actions**, open the published HTTPS site in Edge or Chrome and use the browser's **Install app** option.

## Notes
- Checklist content is for Microsoft Flight Simulator only, not real-world aircraft operation.
- Completion ticks are saved locally in the browser/app profile.
- The app is not affiliated with Microsoft or the aircraft manufacturers.
