# FarmDesk

Offline-first farm manager for poultry, livestock and crops. Installable on phones and computers. No server or build step needed.

## Put it online with GitHub Pages (free)
1. Sign in at github.com and click **New repository**. Name it `farmdesk`, keep it **Public**, click **Create repository**.
2. Click **uploading an existing file**. Drag in everything from this folder: `index.html`, `manifest.json`, `sw.js`, and the `icons` folder. Click **Commit changes**.
3. Go to **Settings > Pages**. Under **Branch**, pick `main` and `/ (root)`, then **Save**.
4. After about a minute your app is live at `https://YOUR-USERNAME.github.io/farmdesk/`.

## Install it
- **Android (Chrome):** open the link, tap **Install** at the top of the app (or menu > Install app).
- **iPhone (Safari):** tap Share > **Add to Home Screen**.
- **Computer (Chrome/Edge):** click the install icon in the address bar.

Open it once with internet. After that it works offline.

## Updating
Edit `index.html`, upload it again, and change `V='farmdesk-v1'` in `sw.js` to `farmdesk-v2` so phones pick up the new version.

## Your data
Records and edited reference data are stored on the device. Use **Today > Backup and restore** to copy a backup.
