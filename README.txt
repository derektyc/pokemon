POKEMON PACK SIMULATOR — SAFE DRIVE + AUTO PLAY PWA

Upload ALL files/folders in this package to the SAME GitHub Pages directory.
The live app must be served as index.html.

Required at the same level:
- index.html
- manifest.webmanifest
- service-worker.js
- .nojekyll
- assets/

Do not upload only the standalone HTML file if you want the installed PWA/update system.

THIS BUILD ADDS
- Google Drive reconnect conflict protection.
- Unsynced local progress is never silently replaced on reconnect.
- If both local and Drive changed, choose This Device / Google Drive / Cancel.
- A local recovery copy is created before a cloud save replaces local progress.
- Auto Play checkbox replaces the old Autoswipe button.
- Auto Play opens the selected pack batch and swipes cards automatically.
- Auto-stop rarity and God Packs pause Auto Play.
- Auto Play starts OFF every time the app launches.
- Profile name derektyc (case-insensitive) gets 1-10 box options plus ∞ Unlimited Boxes at any level.
- Existing responsive binder and PWA install/update features are preserved.

After deployment, open the HTTPS GitHub Pages URL and refresh once so the v4 service worker can update the installed app.
