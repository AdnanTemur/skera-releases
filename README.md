<div align="center">

# Skera — Releases

**A fast, image-first viewer with RAW, EXIF and side-by-side compare.**
One small app for macOS, Windows and Linux.

[**↓ Download the latest version**](https://github.com/AdnanTemur/skera-releases/releases/latest) · [Website](https://skera.nexylius.com) · [Report an issue](https://github.com/AdnanTemur/skera-releases/issues)

</div>

---

This repository hosts the **downloadable builds** of Skera. The application
source is maintained separately; this is the place to get the app itself and
read release notes.

## Download

Grab the file for your system from the [**latest release**](https://github.com/AdnanTemur/skera-releases/releases/latest):

| System | File |
|--------|------|
| **macOS** (Apple Silicon & Intel) | `Skera-macOS.dmg` |
| **Windows** (64-bit) | `Skera-Windows-Setup.exe` |
| **Linux** (portable) | `Skera-Linux.AppImage` |

### Installing

- **macOS** — open the `.dmg` and drag Skera to Applications. On first launch,
  right-click the app and choose *Open* to get past Gatekeeper.
- **Windows** — run the `.exe` installer. If SmartScreen appears, choose
  *More info → Run anyway*.
- **Linux** — make it executable and run it:
  ```bash
  chmod +x Skera-Linux.AppImage
  ./Skera-Linux.AppImage
  ```

### Verifying your download (optional)
Each file ships with a `.sha256` checksum. To confirm a download is intact:

```bash
# macOS / Linux
shasum -a 256 -c Skera-macOS.dmg.sha256

# Windows (PowerShell)
Get-FileHash Skera-Windows-Setup.exe -Algorithm SHA256
```

## What Skera does

- **Reads RAW directly** — NEF, CR2/CR3, ARW, DNG, RAF, ORF and more, with no
  import step.
- **Full EXIF** — body, lens, exposure, ISO and GPS in an Info panel.
- **Side-by-side compare** — lock image A, sweep through B; zoom and pan stay
  linked.
- **Image-first** — the interface hides on command so it's just the picture.
- **Fully keyboard-driven** and built for speed on large folders.

## Privacy

Skera is local-only: no accounts, no servers, no telemetry. Your images never
leave your machine. Full policy: <https://skera.nexylius.com/privacy>.

## Support

Questions or bug reports: open an [issue](https://github.com/AdnanTemur/skera-releases/issues)
or email **adnantemur.se@gmail.com**.

---

<div align="center">
Built by <a href="https://github.com/AdnanTemur">Adnan Temur</a> · <a href="https://nexylius.com">Nexylius</a>
</div>
