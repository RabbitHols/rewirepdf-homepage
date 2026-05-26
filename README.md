# RewirePDF Home

Static homepage for `rewirepdf.com`.

The PDF editor app lives at:

```text
https://app.rewirepdf.com
```

## Local Preview

Open `index.html` directly in a browser, or run a tiny static server:

```bash
python3 -m http.server 8080
```

## Cloudflare Pages

Use these settings:

```text
Build command: none
Output directory: /
```

If Cloudflare requires a command, use:

```text
Build command: true
Output directory: /
```

The project is intentionally dependency-free: HTML, CSS, one small JS file, and
local assets only. The page positions RewirePDF as a UX-friendly open source
PDF editor for everyday operations, real-world PDF support, certificates,
permissions, web/mobile use, installable PWA behavior, and native app work in
progress.

The page language is English.
