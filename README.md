# Matcha — website

Marketing, support, and privacy pages for **Matcha**, a pocket lo-fi instrument for iPhone and iPad.

Static site, hosted on GitHub Pages. No build step.

| Page | File | Used for (App Store Connect) |
|------|------|------------------------------|
| Landing | `index.html` | Marketing URL (optional) |
| Support | `support.html` | **Support URL** (required) |
| Privacy | `privacy.html` | **Privacy Policy URL** (required) |

## Local preview

```sh
python3 -m http.server 8080
# open http://localhost:8080
```

## Notes
- Fonts (Zen Old Mincho, Zen Kaku Gothic New, Space Mono) load from Google Fonts — the same faces the app uses.
- Support / contact email: **zhiii0x@gmail.com**
- `assets/og.png` is the social-share preview (1200×630).
- The App Store link (`https://apps.apple.com/app/id6786523067`) sits in the hero CTA, in every footer, and in the `apple-itunes-app` smart-banner meta on all four pages.
