# Castle Gallery Photos ✦

Drop your photos into this folder (`photos/`) with these **exact** names.
The code asks for `.jpg` only — a `.png` will NOT be picked up, so export
or screenshot-convert them to `.jpg` first.

| File | Where it shows up | Caption under the frame |
|---|---|---|
| `1.jpg` | 1st frame, left wall (nearest the door) | memory 1 · the loud one |
| `2.jpg` | 2nd frame, left wall | memory 2 · sibling chaos |
| `3.jpg` | 3rd frame, left wall | memory 3 · laughing at nothing |
| `4.jpg` | 4th frame, left wall (nearest the arch) | memory 4 · the quiet talks |
| `5.jpg` | 1st frame, right wall (nearest the door) | memory 5 · food wars |
| `6.jpg` | 2nd frame, right wall | memory 6 · our favorite corner |
| `7.jpg` | 3rd frame, right wall | memory 7 · always got your back |
| `8.jpg` | 4th frame, right wall (nearest the arch) | memory 8 · happy 17th, aashika |

Captions live in `js/content.js` → `photoTitles[]`. Change them there, and
change the file names here — both must agree on the order.

## Tips

- **Portrait, roughly 3:4 or 4:5**, looks best — the frames are tall.
- Around **600×800 to 1200×1600 px** is plenty. Anything bigger just makes
  the page slow to load on a phone; keep each file under ~300 KB.
- Faces near the **centre**: the photo is cropped to fit the frame
  (`object-fit: cover` in the pop-up viewer), so anything at the very top
  or bottom edge may be cut off.
- Missing a photo? The frame falls back to a plain purple card, nothing breaks.
