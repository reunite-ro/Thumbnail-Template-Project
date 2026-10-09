# Thumbnail Maker

Make thumbnails and covers for YouTube, TikTok, Instagram, Facebook and your blog from one design, right in your browser. There's nothing to install, no account, and no uploads.

Type a title, pick a template and a style, drop in a photo, and download every size you need.

## Quick start

1. Download or clone this repository.
2. Open `thumbnail-maker.html` in Chrome or Edge (double-click it).
3. Pick a template, type your title, add a photo, and click **Download ticked**.

The fonts load from Google Fonts, so you need an internet connection the first time. Offline, the tool still works with system fonts.

## Sizes

| In the tool | Size (px) | Ratio | Use it for |
|---|---|---|---|
| YouTube | 1280 × 720 | 16:9 | YouTube video thumbnails |
| Vertical 9:16 | 1080 × 1920 | 9:16 | TikTok covers, Instagram Reels covers and Stories, Facebook Reels and Stories |
| Post 4:5 | 1080 × 1350 | 4:5 | Instagram and Facebook feed posts (the recommended feed size) |
| Square | 1080 × 1080 | 1:1 | Instagram and Facebook square posts and carousels |
| Blog / Link | 1200 × 630 | 1.91:1 | Blog featured images, `og:image`, and link previews on Facebook, LinkedIn, X and WhatsApp |

### Safe zones

Turn on **Show safe zones** to see what each platform covers or crops. The guides appear only in the preview, never in the downloaded image.

- **YouTube:** the video length covers the bottom-right corner. Uploads are limited to 2 MB, so the tool lowers JPG quality automatically to stay under it.
- **Vertical 9:16:** TikTok and Instagram profile grids show only the middle 3:4 (1080 × 1440), and captions, buttons and the reply bar cover the top and bottom. Every template keeps its text inside that middle area.
- **Post 4:5:** Instagram's profile grid trims about 34 px from each side.
- **Square:** Instagram's profile grid shows only the middle 810 × 1080 (3:4). The tool keeps text inside it automatically.
- **Blog / Link:** some chat apps crop link previews to a square in the middle.

Instagram's 3:4 size (1080 × 1440) isn't included. It looks best on the profile grid, but a post that size can't be boosted as an ad, so 4:5 is the safer default.

Sizes were checked in October 2026. Platforms change their specs from time to time, so check again if a size starts to look cropped.

## Templates

All 18 templates work in every size. Wide sizes (YouTube, Blog / Link) and tall sizes (Vertical, 4:5, Square) each get their own arrangement of the same design.

| Template | Best for |
|---|---|
| Face + Bold | Huge text plus your cut-out photo. The classic YouTube look. |
| Center Impact | One loud, centered message over a photo. |
| Split | A color panel and a photo with a slanted edge. |
| Listicle | A giant number for "7 tips…" style posts. |
| Reaction | An arrow and circle pointing at something in your photo, plus your face. Move the photo with its sliders to line it up. |
| Neon Glow | Glowing neon colors, a retro grid floor and a glass card. Good for tech topics. |
| Tutorial | Your screenshot in a browser window, for how-to videos. |
| Phone | Your screenshot on a phone, for app and mobile tutorials. |
| Checklist | A heading plus ✓ items. |
| Promo / Sale | A starburst badge and a button, for offers, discounts and launches. |
| Versus | Two sides head to head. |
| Podcast | Round host and guest photos, an episode number and a sound wave. |
| News | A news-style lower third for updates and announcements. |
| Photo Frame | A photo in a bold color frame with a title band. |
| Polaroid | A tilted instant photo with tape and a handwritten caption. A cut-out pops out of the photo. |
| Quote | A quote with your name and photo. |
| Minimal | Big type and lots of space. |
| Clean Article | An editorial look for blog posts. |

## Writing the title

- Wrap words in `*stars*` to highlight them, for example `I Tried *Every* Budget Camera`.
- Press Enter to start a new line.
- **Versus:** write `Shared Hosting vs VPS` (or use `lawan`), and each side gets its own half.
- **Checklist:** the first line is the heading, and each line after it becomes a ✓ item.
- **Quote:** the title is the quote, and the field below it is the author's name.

The text sizes itself as big as it can fit. Three to six words read best at thumbnail size.

The other text fields are:

- **Tag:** the small label above the title.
- **Channel / site name:** shown with your logo.
- **Big number:** for Listicle, or the episode number for Podcast.
- **Badge text** and **Button text:** for Promo.

## Styles

- **Looks:** nine one-click styles that set the font, colors, highlight, effect and background together. They are Bold Pop, Tech Neon, Retro, Clean, Elegant, Playful, Marker, Corporate and Soft.
- **Colors:** 19 presets, or pick your own base, accent and text colors.
- **Headline fonts:** Anton, Bebas Neue, Oswald, Archivo Black, Montserrat, Poppins, Inter, Kanit, Saira, Fredoka, Lilita One, Righteous, Bangers, Permanent Marker and Playfair Display.
- **Highlight:** Box, Brush stroke, Marker or Colored text.
- **Text effect:** Shadow, Outline, Outline + shadow, 3D, Glow or None.
- **Background pattern:** Gradient + lines, Gradient, Dots, Grid, Rays, Color blobs or Solid color. The pattern shows wherever there's no background photo.
- **Text size** slider and an **ALL CAPS** switch.

## Images

| Slot | What it's for | Controls |
|---|---|---|
| Background photo | The main photo, or your screenshot in Tutorial and Phone | Zoom, left ↔ right, top ↕ bottom, darken |
| Cut-out | A transparent PNG of you or a product | Size, left ↔ right, up ↕ down, sticker outline and its color |
| Second cut-out | The right side in Versus, or the guest in Podcast | Uses the cut-out controls |
| Logo / avatar | Shown next to your channel or site name | Auto, Circle or Full logo |

To add an image, click a slot, drag a file onto it, or paste with Ctrl+V. If you drop or paste onto the preview, the tool sorts it for you: photos become the background and transparent PNGs become the cut-out.

To make a transparent PNG, use the **Remove background** button in Windows Paint, or [remove.bg](https://www.remove.bg).

## Downloading

- **Download [size]** saves the size you're looking at.
- **Download ticked** saves every size whose preview has its box ticked. Your browser may ask you to allow multiple downloads the first time.
- Choose JPG for smaller files or PNG for sharper ones. If a YouTube PNG would be over 2 MB, it's saved as a JPG instead.
- Files are named after your title and the size, for example `i-tried-every-budget-camera-post-4x5-1080x1350.jpg`.

## Saving your work

- Your last design is remembered in this browser automatically. Very large photos may not fit in browser storage, but your text, colors and logo are always kept.
- **Save project** downloads a `.thumb.json` file with your text, style and images. **Open project** loads it again, so you can reuse a design as a starting point for your next video or post.
- **Reset to defaults** starts over.

## Privacy

Everything runs on your own computer, and your photos are never uploaded. The only thing loaded from the internet is the fonts, from Google Fonts.

## For developers

Everything lives in `thumbnail-maker.html`: plain HTML, CSS and JavaScript that draw on a `<canvas>`. There's no build step, and the only outside dependency is Google Fonts.

The common changes are all near the top of the `<script>`:

| To add | Edit |
|---|---|
| A color preset | `PALETTES` |
| A Look | `LOOKS`: a font, a palette name, a highlight, an effect and a pattern |
| A font | `FONTS`, and add the family to the Google Fonts `<link>` in `<head>` |
| A size | `FORMATS`: name, size, file name and note. Add its guides in `drawGuides()`. |
| A template | An entry in `TEMPLATES`, plus a drawing function with the same key in `RENDER` |

Each template function receives `g`, which holds:

- `W` and `H`: the canvas size.
- `P`: true for square and taller sizes.
- `pad`: the edge margin.
- `g.Y(f)`, `g.Hh(h)` and `g.u`: helpers for stacked layouts. Each stacked layout is drawn as if on a 9:16 canvas, and these helpers scale it to fit 4:5 and square.
