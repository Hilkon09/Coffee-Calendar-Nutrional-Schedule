# Coffee Schedule

Fertiliser and crop-care schedule for arabica coffee in the Central Rift and South Rift (Kenya). Works offline once installed.

## Get the APK

1. Create a new repository on GitHub (any name).
2. Upload everything in this folder to it, including the hidden `.github` folder. Keep the same folder layout.
3. Open the repository's **Actions** tab. The "Build APK" workflow starts by itself and takes about 5 to 8 minutes. If it does not start, choose "Build APK" and press **Run workflow**.
4. When it finishes, open the repository's **Releases** page and download `coffee-schedule.apk`.
5. On your phone, open the downloaded file and allow "Install unknown apps" when asked.

Every time you change a file and push, a new APK replaces the old one in Releases.

## Changing the content

All schedule text is in `www/app.js` (the `PLAN` list at the top). Colours and layout are in `www/style.css`.
