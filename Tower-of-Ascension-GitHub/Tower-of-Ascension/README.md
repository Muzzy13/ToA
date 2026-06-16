# Tower of Ascension — Desktop App

## Download

Pre-built installers are on the [Releases page](../../releases) or under **Actions → latest build → Artifacts**.

| Platform | File |
|----------|------|
| Windows  | `Tower of Ascension.exe` — portable, just double-click |
| macOS    | `Tower of Ascension.dmg` — drag to Applications |
| Linux    | `Tower of Ascension.AppImage` — make executable, double-click |

---

## Build it yourself

**Requires:** [Node.js 20+](https://nodejs.org)

```bash
npm install
npm run build-win      # → dist/*.exe
npm run build-mac      # → dist/*.dmg
npm run build-linux    # → dist/*.AppImage
```

## Run without building

```bash
npm install
npm start
```
