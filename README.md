# McCrawAI email header

Animated GIF header for gideon@ (and other) McCrawAI emails.

- Mark: the approved Mi logo (`seo-demo/profiles/assets/mccrawai-logo-transparent.svg`), used as-is. No redesign, no added wordmark (the SVG has none).
- Animation: a soft gold glow pulse, then a gold shimmer sweep across the mark, then a rest on the clean logo. Loops.
- First frame is the complete, clean, fully-visible logo (Outlook desktop shows only frame 1).
- Canvas: 600×180, black `#000000` to match the official logo artboard. 127.8 KB, 25 frames, 3.54s loop.
- A 2× (1200×360) GIF was built and discarded because it was over the 300 KB cap.

## Files

| File | Notes |
|---|---|
| `mccrawai-header-600.gif` | The header to use in email HTML (`alt="McCrawAI"`). |
| `mccrawai-header-600-frame1.png` | PNG of frame 1, for preview. |
| `build_header.py` | Rebuild script (Pillow + cairosvg). |

## Public URL

Hosted on GitHub Pages (a full production deploy of mccrawai.com was not used, because that would republish the whole site):

https://mccrawaiops.github.io/email-assets/mccrawai-header-600.gif

Do not edit sender scripts from this folder; another agent wires the URL into the HTML template.
