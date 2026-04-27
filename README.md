# CarAppLab Catalog

App catalog consumed by **CarHub** on the BAW 212 head unit.

## How to add an app

1. Upload the APK as a GitHub Release asset to this repo (tag format: `<id>-<version>`).
2. Upload a 192x192 PNG icon to `icons/<id>.png`.
3. Add a new entry to `catalog.json`.
4. Commit & push. The car app fetches `catalog.json` on launch.

## Catalog URL

`https://raw.githubusercontent.com/ODuwaik/carapplab-catalog/main/catalog.json`
