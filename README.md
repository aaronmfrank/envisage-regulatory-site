# Envisage Regulatory Consulting — website files


[TEST SITE](https://aaronmfrank.github.io/envisage-regulatory-site/)

## What's in the repo

```
/
├── index.html        ← Home
├── services.html     ← What we do
├── team.html         ← Team
├── contact.html      ← Contact
├── style.css         ← Shared stylesheet
├── images/
│   └── logo.png      ← Logo (replace with higher-quality version when ready)
└── README.md         ← This file
```

## Placeholders to replace before going live

Search the HTML files for these strings — they all need to be updated with real content.

**Team page (team.html):**
- `[First Name] [Last Name]` — both team members
- `FN` (the placeholder initial circles) — once real headshots are available, replace `<div class="team-detail-photo">FN</div>` with `<img src="images/yourname.jpg" alt="...">` and add a corresponding CSS class
- Bio paragraphs

**Contact page (contact.html):**
- `doreen@envisageregulatory.com` — real email
- `+1 (XXX) XXX-XXXX` — real phone (or remove the block)
- `[City, State]` — real location

**All pages:**
- `© 2026 Envisage Consulting, LLC` — year if applicable

## How to update content

Edit the relevant `.html` file via the GitHub web UI:
1. Open the file in your repo
2. Click the pencil icon (top right)
3. Edit
4. Commit changes
5. Site updates automatically within ~60 seconds

## How to swap the logo

1. Save the higher-quality logo as `logo.png` in the `/images/` folder
2. Commit
3. Done

If you want the logo to appear in the navigation (instead of the text-based "envisage" wordmark currently used), replace `<a href="index.html" class="nav-brand">...</a>` with `<a href="index.html"><img src="images/logo.png" style="height: 40px;" alt="Envisage"></a>` in all four HTML files.

## Color palette (in style.css under :root)

- **Cream:** `#F4EBDC` (page background)
- **Cream light:** `#FAF4E8` (alt section background)
- **Ink:** `#2A1F2E` (primary text, dark sections)
- **Purple:** `#5C1B8E` (brand primary — pulled from logo)
- **Red:** `#C8102E` (accent — pulled from logo)

Change these in one place and the whole site updates.

## Fonts

- **Cormorant Garamond** (serif, editorial headlines)
- **Inter** (sans-serif, body)

Both load from Google Fonts — no setup needed.
