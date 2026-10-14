# Patchogue Flooring — War Room

Tron/Iron-Man HUD lead command app. Live via GitHub Pages.

## Regenerate

```bash
cd ~/workspace/patchogue-flooring-marketing
python3 build_site.py   # reads the lead CSVs, emits war-room-site/index.html
cp war-room-site/index.html ~/workspace/war-room-site-repo/
cd ~/workspace/war-room-site-repo && git add -A && git commit -m "refresh" && git push
```

Pages redeploys automatically on push to `main`.
