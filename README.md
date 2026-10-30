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
- Tap the map (or the place name) in a photo's info to open that spot in Apple Maps (maps.apple.com). Adjust opens the location editor.
- The preview map and the editor use MapLibre GL JS with the open-source Apple Maps look from github.com/dddevid/MapLibre-GL-JS-AppleMaps-Style (dark for Standard, white for Light), with map data from OpenFreeMap and OpenStreetMap. Satellite uses Esri imagery. Place search and place names use OpenStreetMap Nominatim.
- Settings > Metadata turns location tagging on or off. Photos and videos never leave your phone.
