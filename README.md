# Ông Tây Quán — Website Mockup

A premium dark-themed one-page website mockup for Ông Tây Quán, a Western steakhouse in Thủ Dầu Một, Bình Dương. Built as a Stream 6 (website-building service) demo/prospect example — not a live client site.

## What's real vs. placeholder

**Real (pulled from Tripadvisor/Foody):**
- Address: 117 Hoàng Văn Thụ, P. Chánh Nghĩa, Thủ Dầu Một, Bình Dương
- Hours: Daily, 11:30 AM – 10:00 PM
- Cuisine: Steakhouse, Vietnamese, American, Mexican, Italian
- Rating: 4.1/5 on Tripadvisor, #12 of 50 restaurants in Thủ Dầu Một

**Now real (boss's own photos, dropped onto Desktop 2026-10-08, 14 of 35 used):**
- `assets/hero-poster.jpg` — real photo: ribeye steak plate with beer and the restaurant's actual brick-wall interior visible in the background. Ken Burns zoom/pan animates directly on this real photo now (genuinely visible — verified live via pixel diff and direct JS computed-style checks, not just claimed).
- `assets/menu-steak.jpg`, `assets/menu-beef.jpg`, `assets/menu-western.jpg`, `assets/menu-seafood.jpg` — real dish photos (sliced ribeye, lamb chops, burger & fries, seared tuna).
- `assets/gallery-1.jpg` through `gallery-9.jpg` — real photos: table spreads, outdoor terrace, burger bite, salad, pasta, seafood fried rice, shrimp plate.
- These are the 14 strongest/most varied shots curated from the 35 photos boss provided — more can be swapped in or added if a bigger gallery is wanted.
- Menu card 4 was relabeled from the original placeholder "Mexican Fare" to "Seafood & Asian-Fusion" to honestly match the real photo used (seared tuna) — no Mexican dish was in the photo set, so the copy wasn't left claiming something the image doesn't show.

**Still placeholder:**
- `assets/hero-video.mp4` — no real video file yet, the CSS Ken Burns zoom on the real hero photo is the fallback and works well on its own. Drop in a real looping video here if/when one exists; a ready-to-use AI video generation prompt (steak sizzling, flames, chef plating) is banked in the project's email thread if needed later.
- The reviews section pulls the real aggregate rating (4.1/5) but does NOT include fabricated customer quotes — per standing rule, no fake testimonials. Swap in 3-4 real pulled guest quotes once available.
- The reservation form is front-end only (no backend) — connect it to a real booking system before going live.

## How to preview locally

Open `index.html` directly in a browser, or run a simple local server from this folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
