# SpeqAI Landing Page

A sleek, modern landing page for SpeqAI — the voice AI client app.

## Preview

Open `index.html` in a browser to preview locally.

## Features

- 🎨 Dark mode with gradient accents (indigo/violet/pink)
- ✨ Animated background with subtle noise texture
- 🎙️ Voice visualizer animation in hero section
- 📱 Phone mockup with pulsing talk button
- 📧 Email signup form (ready to connect to backend)
- 📐 Fully responsive (mobile-first)
- ⚡ Zero dependencies — pure HTML/CSS

## Deploy to Cloudflare Pages

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Connect your GitHub repo or upload directly
3. Set the custom domain to `speqai.com` or `speqai.app`
4. Done!

### Quick Deploy (Direct Upload)

```bash
# If you have wrangler CLI installed
npx wrangler pages deploy . --project-name=speqai
```

## Customization

### Colors (in `:root`)
- `--accent-primary`: Main accent (indigo #6366f1)
- `--accent-secondary`: Secondary (violet #8b5cf6)  
- `--accent-tertiary`: Accent pop (pink #ec4899)

### Fonts
- **Headings**: Space Grotesk (Google Fonts)
- **Body**: Inter (Google Fonts)

## Email Form

The email form currently has no backend. Options to wire it up:

1. **Cloudflare Workers** — Simple serverless function
2. **Formspree** — Free form backend
3. **ConvertKit/Mailchimp** — Email list services
4. **Supabase** — Database + Edge Functions

## Files

```
speqai-landing/
├── index.html    # Complete landing page
└── README.md     # This file
```

---

Built with 💜 by Natalie
