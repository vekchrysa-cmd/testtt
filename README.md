# gov.gr wallet – interactive clone

## Files

| File | Purpose |
|------|---------|
| `index.html` | Outer shell – switches between screens |
| `login.html` | Login / splash screen |
| `home.html` | Home with swipeable ID + Driver Licence carousel |
| `menu.html` | Side menu |
| `index_original.html` | **Original detailed ID view – appearance never changed** |
| `apple-icon.png` | App icon (copy from old repo if you have it) |

## How to use

1. Upload all files to a new GitHub repository (or any static host).
2. Open `index.html`.
3. Edit the `DATA` object at the top of `home.html` and `menu.html` to change name, photo, ID number, etc.
4. The detailed ID screen (`index_original.html`) keeps the exact original look, background image, and layout.

## Navigation

- Login → Home (TaxisNet button)
- Home → Detail (tap the ID card)
- Home → Menu (hamburger)
- Menu → Home (tabs / Αρχική)
- Detail has its own original QR popup (white background)
