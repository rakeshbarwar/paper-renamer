<p align="center">
  <img src="icon.png" width="120" alt="Paper Renamer icon">
</p>

<h1 align="center">Paper Renamer</h1>

<p align="center">Rename downloaded research-paper PDFs to <b>Year-Author-Title</b> — automatically.</p>

---

Paper Renamer reads each PDF's DOI (or its title), looks up the real citation, and
renames the file to a clean `Year-Author-Title.pdf`. You choose which files to
rename; anything it isn't sure about is left exactly where it is.

## Download

### → [**Download the latest version**](https://github.com/rakeshbarwar/paper-renamer/releases/latest)

| Your computer | File to download |
|---|---|
| **Windows 10 / 11** | `Paper-Renamer-Windows.exe` |
| **Mac — Apple Silicon** (M1, M2, M3, M4) | `Paper-Renamer-AppleSilicon.dmg` |
| **Mac — Intel** | `Paper-Renamer-Intel.dmg` |

Not sure which Mac you have? **Apple menu → About This Mac** and look at "Chip" or
"Processor" — "Apple M…" = Apple Silicon, "Intel…" = Intel.

## Install & open

### Windows
1. Download **`Paper-Renamer-Windows.exe`** (it's a single file — nothing to unzip).
2. Double-click it.
3. The first time, Windows may say *"Windows protected your PC"* → click
   **More info → Run anyway**.

> Needs the Microsoft Edge WebView2 Runtime, which is already installed on Windows 11.

### macOS
1. Download the right **`.dmg`**, open it, and drag **Paper Renamer** into your
   **Applications** folder.
2. macOS blocks apps from outside the App Store on first launch. Open the
   **Terminal** app and run this **once**:

   ```
   xattr -dr com.apple.quarantine "/Applications/Paper Renamer.app"
   ```

3. Now open **Paper Renamer** normally (from Applications or Launchpad).

> You only need step 2 once. It tells macOS the app is safe to run.

## How to use it

1. **Look in** — the folder to scan (defaults to your Downloads).
2. **Move renamed to** — where tidy papers should go (defaults to Documents/Papers).
3. Click **Preview**. Every PDF is listed with a **confidence %** on the right.
   Confident matches are **ticked automatically**.
4. Tick or untick any file. Use **Select all**, or click the
   **Confident / Review / No match** chips to filter the list.
5. Click **Rename Now** — only the **ticked** files are renamed and moved.
6. **Undo Last** reverses the most recent rename.

Other niceties: a **Light / Dark / Auto** appearance switch (top-right), and files
the app can't confidently identify are always left untouched.

> Needs an internet connection — it looks papers up on [Crossref](https://www.crossref.org/).

---

<p align="center"><sub>© 2026 Rakesh Barwar</sub></p>
