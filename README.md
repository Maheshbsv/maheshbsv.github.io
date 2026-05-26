# maheshbsv.github.io

Personal resume website for **Mahesh Babu S V**, hosted via GitHub Pages at [maheshbsv.github.io](https://maheshbsv.github.io).

## About

A single-page interactive resume built with vanilla HTML, CSS, and JavaScript — no frameworks or build tools required.

**Design features:**
- Glassmorphism dark theme with animated aurora background
- Scroll-reveal animations and a reading progress bar
- Interactive skill tags, hover effects, and a vertical experience timeline
- Lightbox photo gallery for event highlights
- Fully responsive — works on mobile and desktop
- Print-friendly stylesheet

## Structure

```
├── index.html                        # Main resume page
├── resume.md                         # Source content (plain text)
├── images/
│   └── aws_summit_bengaluru_2025/    # Event photos
│       ├── aws_summit_bengaluru_1.jpg
│       └── aws_summit_bengaluru_2.jpg
└── appreciations/                    # Additional assets
```

## Adding content

**New event with photos:**
1. Create a folder under `images/` (e.g. `images/my_event_2026/`)
2. Drop your photos in it
3. Copy an `event-card` block in `index.html` and update the image paths, title, date, and description

**New job / experience entry:**
- Copy a `t-entry` block inside the `.timeline` div in `index.html`

## Deployment

Push to the `main` branch — GitHub Pages publishes automatically.

