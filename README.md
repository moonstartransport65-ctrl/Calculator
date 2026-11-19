# Worksheet Calculator

Tape-style calculator with history, editable amounts, titles and subtotals.

## Folder layout
- `www/index.html`  : the whole app (HTML, CSS, JS in one file)
- `capacitor.config.json`, `package.json` : Android wrapper settings
- `.github/workflows/build-apk.yml` : builds the APK automatically on GitHub

## Make the APK (no computer tools needed)
1. Create a new repository on GitHub.
2. Upload ALL the files and folders from this zip (keep the folder names, including the hidden `.github` folder).
3. Open the **Actions** tab. The "Build APK" job starts by itself (or press "Run workflow").
4. When it turns green (about 5 to 8 minutes), open the run and download **worksheet-calculator-apk** at the bottom (Artifacts).
5. Unzip it and install `app-debug.apk` on your phone (allow "Install unknown apps" if asked).

## Test without APK
Open `www/index.html` in Chrome.

## Ads
No ad code is included. To add AdMob later, a Capacitor AdMob plugin and your own AdMob app ID are needed.
