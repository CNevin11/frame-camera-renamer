# Frame to Camera Renamer (Web App)

This GitHub Pages app allows you to:
- Upload a `.csv` with frame-to-camera ID mappings
- Upload a batch of `.jpeg` images with padded or unpadded frame numbers (e.g. `0001.jpg`, `1.jpg`, etc.)
- Automatically rename and download a ZIP of renamed images

## How to Deploy

1. Go to [github.com](https://github.com) and create a **new repository**. Example name: `frame-camera-renamer`.
2. Upload all the files from this ZIP into the repository.
3. Go to **Settings > Pages**
4. Under "Source", choose `main` branch and `/ (root)` directory, then click Save.
5. Wait 1–2 minutes — your app will be live at:
   `https://<your-username>.github.io/frame-camera-renamer/`

## Example CSV Format

```
1,SId-123456789
2,SId-123456788
...
```

- Filenames like `img_00001.jpeg` → extract `1`, match `SId-123456789`
