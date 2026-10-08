# Ông Tây Quán — Website Mockup

A premium dark-themed one-page website mockup for Ông Tây Quán, a Western steakhouse in Thủ Dầu Một, Bình Dương. Built as a Stream 6 (website-building service) demo/prospect example — not a live client site.

## What's real vs. placeholder

**Real (pulled from Tripadvisor/Foody):**
- Address: 117 Hoàng Văn Thụ, P. Chánh Nghĩa, Thủ Dầu Một, Bình Dương
- Hours: Daily, 11:30 AM – 10:00 PM
- Cuisine: Steakhouse, Vietnamese, American, Mexican, Italian
- Rating: 4.1/5 on Tripadvisor, #12 of 50 restaurants in Thủ Dầu Một

**Placeholder (needs real assets before this goes live anywhere):**
- `assets/hero-video.mp4` — hero banner video, not included. Drop in an 8-15s silent looping clip (steak on the grill, flame, plating shot). Keep it under ~5-8MB, H.264 MP4. Until that file exists, the hero uses a CSS Ken Burns zoom/pan + pulsing ember-glow overlay on the poster image so it still feels alive, not static.
- `assets/hero-poster.jpg` — fallback image shown before the video loads / on slow connections.

**Ready-to-use AI video generation prompt** (paste into Veo 3.1, Kling, or similar — covers the "steak sizzling, flames, chef plating, looping silently behind the headline" brief):

> Cinematic close-up, 8-second seamless loop, no audio needed. A thick ribeye steak sizzling on an open flame grill, orange flames licking up around the edges, visible char marks forming, steam and light smoke rising. Slow motion, shallow depth of field, warm amber and orange lighting, dark moody restaurant background blurred out. Camera holds a static low-angle close shot, no cuts. Ultra-sharp HD, high-resolution 4K, cinematic color grade, no text, no logos, no people's faces — purely the steak, flame, and grill.
- `assets/menu-*.jpg`, `assets/gallery-*.jpg` — placeholder image slots for real food/interior photos.
- The reviews section pulls the real aggregate rating (4.1/5) but does NOT include fabricated customer quotes — per standing rule, no fake testimonials. Swap in 3-4 real pulled guest quotes once available.
- The reservation form is front-end only (no backend) — connect it to a real booking system before going live.

## How to preview locally

Open `index.html` directly in a browser, or run a simple local server from this folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
