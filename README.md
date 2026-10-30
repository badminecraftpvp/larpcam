# LarpCam

A camera-style web app that plays your own videos as the "live view". Installable on your phone (PWA).

## Put it online
1. Create a new repo on github.com and upload every file in this folder (keep them at the top level, no subfolders).
2. On vercel.com: Add New > Project > import the repo > Deploy. No settings needed.

## Install on your phone
- iPhone: open your Vercel link in Safari > Share > Add to Home Screen.
- Android: open it in Chrome > menu > Install app.

Footage you add is stored on the phone only (IndexedDB), never uploaded.

## Gallery, info and map
- Tap the thumbnail (bottom left) to open the gallery. Open a photo or video and swipe up (or tap the info button) to see its details and map.
- Maps use OpenStreetMap and Esri satellite tiles through Leaflet. Place search and place names use OpenStreetMap Nominatim. These need an internet connection. Everything else works offline.
- Settings > Metadata turns location tagging on or off. Photos and videos never leave your phone.
