<div align="center">

# `dlvidz` 📼

### PASTE A LINK. GET A COMMAND. KEEP IT LOCAL.

**A tiny, retro-flavoured command generator for [yt-dlp](https://github.com/yt-dlp/yt-dlp).**

![Static HTML](https://img.shields.io/badge/100%25-STATIC_HTML-8ABF83?style=for-the-badge&labelColor=202822)
![Local first](https://img.shields.io/badge/LOCAL-FIRST-EED49F?style=for-the-badge&labelColor=202822)
![No sign up](https://img.shields.io/badge/NO-SIGN_UP-9DCFE0?style=for-the-badge&labelColor=202822)

`[ macOS ]` · `[ Windows ]` · `[ Linux ]`

**[Open the command generator](./index.html)** · **[yt-dlp supported sites](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md)**

</div>

---

## `01` / WHAT IS THIS?

`dlvidz` is a minimal webpage that helps you install **yt-dlp**, select a video platform, paste a URL, and generate a ready-to-copy download command.

**The website does not download videos or execute commands.** You run the generated command yourself in your own terminal.

```text
  ┌─────────────────────────────────────────────────────┐
  │  dlvidz                                     ● LOCAL │
  ├─────────────────────────────────────────────────────┤
  │                                                     │
  │  PASTE A LINK.                                      │
  │  GET A COMMAND.                                     │
  │  DOWNLOAD LOCALLY.                                  │
  │                                                     │
  │  [ 1. Pick your OS      ]                           │
  │  [ 2. Paste a video URL ]                           │
  │  [ 3. Copy the command  ]                           │
  │                                                     │
  └─────────────────────────────────────────────────────┘
```

## `02` / GET STARTED

1. **Get the page:** Clone this repository or download it as a ZIP.
2. **Open `index.html`:** Double-click the file in your browser. No web server required.
3. **Install dependencies:** Choose **macOS**, **Windows**, or **Linux** and follow the on-page steps to install `yt-dlp` and `ffmpeg` as needed.
4. **Build your command:** Select the source, paste an accessible video URL, then choose your format and optional browser authentication.
5. **Copy → paste → run:** Execute the generated command in Terminal on macOS/Linux or PowerShell on Windows.

```bash
git clone https://github.com/jimjwong/dlvidz.git
cd dlvidz
# Open index.html with your preferred browser
```

> **Privacy by design:** The command generator is static HTML, CSS, and JavaScript. It has no application backend, user accounts, or built-in analytics. The URL you enter is processed in your browser. Running the copied command contacts the video source through yt-dlp.

## `03` / FEATURES

| Feature | What you get |
| :-- | :-- |
| 🖥️ Cross-platform guide | macOS, Windows, and Ubuntu/Debian Linux instructions |
| 🔗 Link to command | Paste a supported URL and generate a `yt-dlp` command |
| 📋 One-click copy | Copy instructions and generated commands |
| 🎚️ Download options | Video/audio modes, subtitles, and playlist options |
| 🔐 Signed-in access | Optional browser-cookie argument for content you can access |
| 🧩 Zero-build setup | A single static HTML app; no app installation or account required |

## `04` / GOOD TO KNOW

- Supported websites and download success depend on **[yt-dlp](https://github.com/yt-dlp/yt-dlp)**, the source site, and your permissions.
- Downloads happen **on your computer**, not on a server operated by dlvidz.
- Restricted content may require a signed-in browser session. The tool does **not** bypass DRM or access controls.
- The Linux setup guide targets **Ubuntu/Debian**; other distributions can follow the [official installation guide](https://github.com/yt-dlp/yt-dlp/wiki/Installation).
- Windows instructions use **PowerShell** and `winget`.

## ⚠️ DISCLAIMER / EDUCATIONAL USE ONLY

> This page is provided for educational and informational purposes. We do not advocate, encourage, or condone illegal downloading, copyright infringement, or bypassing access restrictions. Only download content you own or are authorized to save, and respect applicable laws and platform terms.

---

<div align="center">

**`dlvidz`** · SMALL TOOL, NO FUSS.

<sub>Independent project · Not affiliated with yt-dlp or any video platform.</sub>

</div>
