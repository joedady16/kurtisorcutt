# Photo migration inventory (not yet transferred)

The site currently references five distinct photographs/graphics hosted on the former Yola `/resources/` paths. These must be downloaded from original sources or supplied as files before replacing their URLs.

| Proposed local path | Existing remote resource | Used on |
|---|---|---|
| assets/images/home-portrait.jpeg | https://www.kurtisorcutt.com/resources/03.jpeg | style.css (homepage hero) |
| assets/images/wedding.jpg | https://www.kurtisorcutt.com/resources/IMG-20240815-WA0005.jpg.opt464x618o0%2C0s464x618.jpg | index.html, gallery.html |
| assets/images/coat-of-arms.png | https://www.kurtisorcutt.com/resources/COATOFARMSPLAIN_8.7.24.png.opt502x640o0%2C0s502x640.png | index.html |
| assets/images/ceremonial.jpg | https://www.kurtisorcutt.com/resources/1000014466.jpg | service.html, gallery.html |
| assets/images/holy-land.JPG | https://www.kurtisorcutt.com/resources/106_0669.JPG.opt738x550o0%2C0s738x550.JPG | gallery.html |

## Deployment safeguard
Do not replace external URLs with local paths until each corresponding image file is actually present on the branch and loads successfully. After importing, update the five URLs in HTML/CSS, inspect image response status, and test phone and desktop rendering before merging the PR.

**Status:** responsive CSS changes prepared; image binary migration blocked pending accessible source files. No live-site changes from this branch.
