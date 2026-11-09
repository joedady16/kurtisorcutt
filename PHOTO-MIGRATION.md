# Photo migration — verified inventory

The photographs were uploaded to `assets/images/` on the `main` branch. The responsive and photo-reference changes in this pull request use these existing images. The 13 expected image paths were checked through GitHub on 2026-11-09; binary file responses indicate the image files are present.

## Used by the website changes
- `assets/images/home-portrait.jpg` — homepage hero in `style.css`
- `assets/images/wedding.jpg` — family section and gallery
- `assets/images/coat-of-arms.png` — homepage honors section
- `assets/images/ceremonial.jpg` — service page and gallery
- `assets/images/portrait-31.jpg`, `couple-formal.jpg`, `portrait-alternate.jpg`, `imperial-house.jpg` — gallery

## Other uploaded assets
- `assets/images/portrait-42.jpg`
- `assets/images/portrait-44.jpg`
- `assets/images/portrait-48.jpg`
- `assets/images/gallery-additional-1.jpg`
- `assets/images/gallery-additional-2.jpg`

The original Holy Land photograph was not part of the uploaded set; the third featured gallery image is instead labeled "Additional Portraits." Remaining historical gallery categories are textual placeholders.

## Verification
All local image references in `index.html`, `gallery.html`, `service.html` and `style.css` match files already on `main`. The PR does not need to add binary assets itself. Visual cross-device rendering has not been independently confirmed.
