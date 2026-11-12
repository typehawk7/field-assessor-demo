# Demo walkthrough file

The browser demo loads `composeApp/src/wasmJsMain/composeResources/files/walkthrough.json` and the JPEGs in `composeResources/files/photos/`.

The bundled file is the approved 4518 Chalk Flts, San Antonio move-out export: 16 rooms in walk order, audio `mm:ss` ranges, 78 line items, proposal text, estimate, tenant and owner charges, normalized approval, and totals. Photos are mapped on each room. Each item's `photos` list is empty; the demo spreads that room's photos across its items, and a selected photo can be cited onto a different item.

Tag codes stay in the JSON. The screen maps them to words (Finish, Review, Normal, Note, Professional, Cleaning, Vendor, Highlight). `SEC` is a section header and is not shown as a chip.

The route can be reordered before the walk starts. Review lists rooms in that order. **Cite photo** adds a picture to a line and marks it manual. The first spread of room photos is not manual.

Google spreadsheet and Drive folder ids from the packaging notes are not in this file.

Image paths in the JSON are basenames. The loader reads `files/photos/<filename>`.
