# Castle Gallery Photos ✦

Drop your photos into this folder (`photos/`) with these **exact** names.
The code asks for `.jpg` only — a `.png` will NOT be picked up, so export
or screenshot-convert them to `.jpg` first.

The gallery has 5 frames: two on the left wall, two on the right wall, and
one grand frame on the back wall.

| File | Where it shows up | Label in the pop-up |
|---|---|---|
| `1.jpg` | left wall, first frame (nearest the door) | CUTE |
| `2.jpg` | left wall, second frame (nearest the arch) | PRETTY |
| `3.jpg` | right wall, first frame (nearest the door) | GORGEOUS |
| `4.jpg` | right wall, second frame (nearest the arch) | STUNNING |
| `5.jpg` | back wall, the grand centerpiece | THE PRETTIEST ♡ |

Captions live in `js/content.js` → `photoTitles[]`. Change them there, and
change the file names here — both must agree on the order.

## Tips

- **Each frame keeps the photo's own aspect ratio** — portraits stay tall
  (1.jpg, 3.jpg, 5.jpg) and landscapes stay wide (2.jpg, 4.jpg).
- Around **600×800 to 1200×1600 px** is plenty. Anything bigger just makes
  the page slow to load on a phone; keep each file under ~300 KB.
- Faces near the **centre**: the photo is cropped to fit the pop-up viewer
  (`object-fit: cover`), so anything at the very top or bottom edge may be
  cut off there.
- Missing a photo? The frame falls back to a plain purple card, nothing breaks.
