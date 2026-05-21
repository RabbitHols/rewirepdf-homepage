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
local assets only. The page now mentions the RewirePDF app's installable PWA
mode, offline app shell, local file picker workflow, and no automatic PDF
document storage.

The default page language is English. Use `?lang=it` to force Italian and
`?lang=en` to force English.
