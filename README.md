# Ông Tây Quán — Website Mockup

A premium dark-themed one-page website mockup for Ông Tây Quán, a Western steakhouse in Thủ Dầu Một, Bình Dương. Built as a Stream 6 (website-building service) demo/prospect example — not a live client site.

## What's real vs. placeholder

**Real (pulled from Tripadvisor/Foody):**
- Address: 117 Hoàng Văn Thụ, P. Chánh Nghĩa, Thủ Dầu Một, Bình Dương
- Hours: Daily, 11:30 AM – 10:00 PM
- Cuisine: Steakhouse, Vietnamese, American, Mexican, Italian
- Rating: 4.1/5 on Tripadvisor, #12 of 50 restaurants in Thủ Dầu Một

**Placeholder (needs real assets before this goes live anywhere):**
- `assets/hero-video.mp4` — hero banner video, not included. Drop in an 8-15s silent looping clip (steak on the grill, flame, plating shot). Keep it under ~5-8MB, H.264 MP4.
- `assets/hero-poster.jpg` — fallback image shown before the video loads / on slow connections.
- `assets/menu-*.jpg`, `assets/gallery-*.jpg` — placeholder image slots for real food/interior photos.
- The reviews section pulls the real aggregate rating (4.1/5) but does NOT include fabricated customer quotes — per standing rule, no fake testimonials. Swap in 3-4 real pulled guest quotes once available.
- The reservation form is front-end only (no backend) — connect it to a real booking system before going live.

## How to preview locally

Open `index.html` directly in a browser, or run a simple local server from this folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
