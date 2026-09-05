MemoryFrame v0.11 COLLECTIONS test set

Contains:
- gallery.json
- photos/0000.jpg ~ photos/0011.jpg (12 images, 1920x1080)

Test coverage:
- 2026-07 / 08 / 09 month navigation
- multiple days in September
- tags: Mayo, Kaguya, WorldTour, Night, DosChat, Portrait
- favorites on/off
- collections: World Tour, Night, DosChat, Best Shots, Portrait
- some photos belong to multiple collections
- enough images to exercise pagination when the grid has 8 slots

Upload:
Replace/upload gallery.json and the photos folder contents to the GitHub Pages repository.
Expected public paths:
  /memoryframe/gallery.json
  /memoryframe/photos/0000.jpg ... /0011.jpg

IMPORTANT:
MemoryFrame's predeclared VRCUrl photoUrls array must include slots 0 through 11.
If your current setup only has 0000 and 0001 assigned, add/prepopulate 0002~0011 before testing.
