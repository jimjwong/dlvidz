# dlvidz — command generator

Minimalist, static, local-first download command generator for yt-dlp.

## Disclaimer — Educational Use Only

This page is provided for educational and informational purposes. We do not advocate, encourage, or condone illegal downloading, copyright infringement, or bypassing access restrictions. Only download content you own or are authorized to save, and respect applicable laws and platform terms.

## Use

Open `index.html` in any modern browser. There is no server, package install, build step, account, or telemetry.

Choose your OS, copy the install instructions, enter a video URL, choose optional login browser and download mode, then copy the generated command into your Terminal (Mac/Linux) or PowerShell (Windows).

## Local setup

Save the `dlvidz` folder anywhere on your computer (for example, `~/Projects/dlvidz` on macOS/Linux or `Documents\dlvidz` on Windows), then open `index.html` in a browser.

You can host the HTML on a static website; everything runs locally in the browser.

## Limitations

`yt-dlp` determines supported platforms. Authentication and DRM restrictions apply. The commands generated here do not bypass DRM. For authenticated videos, be sure you are signed into the same browser profile used by yt-dlp.

On Linux, installation instructions target Ubuntu/Debian. Other distributions should use yt-dlp's official install documentation.

Windows instructions target PowerShell and require winget.