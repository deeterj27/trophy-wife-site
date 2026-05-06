---
version: alpha
name: TROPHYWIFE
description: Glossy finishing salt as a fashion accessory — cheeky, collectible, premium, and built to stop the scroll.
colors:
  primary: "#141414"
  secondary: "#5C5357"
  tertiary: "#C8242F"
  neutral: "#F0E6D0"
  trophy-pink: "#D61D6A"
  powder-blush: "#F7EAF2"
  butter-gold: "#D9A441"
  cinnamon: "#9B4A2D"
  pearl: "#FFFAF0"
  on-dark: "#F0E6D0"
  on-hot: "#FFFFFF"
  on-light: "#141414"
typography:
  logo:
    fontFamily: Archivo Black
    fontSize: 1.45rem
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: "0.11em"
    fontStyle: italic
  h1:
    fontFamily: Bodoni Moda
    fontSize: 5.25rem
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.05em"
  h2:
    fontFamily: Bodoni Moda
    fontSize: 3.5rem
    fontWeight: 900
    lineHeight: 0.96
    letterSpacing: "-0.04em"
  h3:
    fontFamily: Bodoni Moda
    fontSize: 1.65rem
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.03em"
  body-md:
    fontFamily: Satoshi
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.7
  label-caps:
    fontFamily: Archivo
    fontSize: 0.72rem
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "0.16em"
  button:
    fontFamily: Archivo
    fontSize: 0.78rem
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "0.12em"
rounded:
  none: 0px
  sm: 2px
  md: 8px
  pill: 9999px
spacing:
  xs: 6px
  sm: 10px
  md: 18px
  lg: 28px
  xl: 52px
  xxl: 96px
components:
  button-primary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-hot}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 16px
  button-primary-hover:
    backgroundColor: "{colors.trophy-pink}"
    textColor: "{colors.on-hot}"
  button-secondary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: 16px
  product-card:
    backgroundColor: "{colors.pearl}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 22px
  editorial-panel:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.none}"
    padding: 64px
---

## Overview

TROPHYWIFE is not a pantry brand. It is finishing salt dressed like a beauty drop: a little provocative, a little expensive, and very aware that the best products get photographed before they get used. The visual identity should feel like a glossy bag spill, a flash-photo dinner party, a lipstick-red campaign poster, and a specialty-food product all at once.

The brand rule: **this salt has a social life.** Pages should feel more like fashion/accessory commerce than rustic food ecommerce. Use campaign language, tight edits, big flavor personalities, sticker-like utility notes, and confident negative space. Avoid farmers-market craft clichés, beige wellness minimalism, generic Shopify cards, and polite serif editorial layouts that make the brand feel too respectable.

## Colors

- **Primary / Vanity Black ({colors.primary}):** Main contrast surface. Use for hero/editorial panels, footer, product set moments, and anything that needs nightlife polish.
- **Tertiary / Lipstick Red ({colors.tertiary}):** Primary conversion color for buttons, product ribbons, hover states, and urgent commerce moments.
- **Trophy Pink ({colors.trophy-pink}):** Brand heat. Use for campaign sections, italic punchlines, stickers, and social/club moments.
- **Neutral / Champagne Cream ({colors.neutral}):** Warm page base. It should feel like packaging paper, not sterile white.
- **Powder Blush ({colors.powder-blush}):** Secondary calm background for product and story sections.
- **Butter Gold ({colors.butter-gold}) and Cinnamon ({colors.cinnamon}):** Flavor accent colors. Use as supporting product cues, not global UI drivers.
- **Pearl ({colors.pearl}):** Product-card surface. Use when a card needs to feel cleaner and more shoppable than the surrounding campaign page.

## Typography

Use **Bodoni Moda** for big campaign headlines: dramatic, high-contrast, fashion-magazine energy. Set it large, tight, and slightly dangerous. Use italic selectively for punchlines and flirtation, not entire paragraphs.

Use **Archivo / Archivo Black** for the wordmark, navigation, labels, product ribbons, CTAs, and utilitarian commerce text. It gives the brand its loud packaging/merch energy. Logo treatments may be italicized/skewed and tracked wide.

Use **Satoshi** for body copy. Body text should stay clean so the wit is readable, but key phrases should be pulled into labels, stickers, cards, or campaign strips instead of buried in long paragraphs.

## Layout

Lead with a campaign moment, not a product grid. The preferred homepage flow is:

1. Announcement bar with active flavors / shipping promise.
2. Sticky nav with loud wordmark, shop/story/use/wholesale, cart.
3. Split hero: editorial image + black campaign panel + primary shop CTA.
4. Accessory-positioning strip: Counter / Clutch / Cocktails / Cart.
5. Philosophy statement: "Not your grandma's salt shaker."
6. Three-flavor core collection with shoppable product cards.
7. Trophy Set bundle upsell.
8. Concept section: salt as accessory.
9. Founder/story proof.
10. Five-minute finishing school.
11. Social proof / content tile.
12. Club/email capture.

Do not run two full Trophy Set sales modules on the same page. Keep one strong bundle upsell directly after the product cards, then use lighter shop/club CTAs later.

Keep grids tidy enough to shop, but interrupt long runs with campaign strips, oversized type, sticker badges, and close-cropped photography. Product cards should feel collectible and beauty-adjacent, not grocery catalog.

## Shapes

Edges are mostly sharp. Rounded corners should be rare and deliberate: pills for badges, tiny radius on cards, no bubbly SaaS components. Use thin black borders, hard color blocks, and sticker/ribbon labels.

## Components

- `button-primary` is lipstick red, square, all caps, and high contrast. It should say the action clearly: **Shop The Salts**, **Get The Trophy Set**, **Add To Cart**.
- `button-secondary` is black/cream or outlined depending on surface. Use for bundle/story CTAs.
- `product-card` should include a flavor ribbon, bold image, short description, price, and CTA. Descriptions stay short; product pages carry the full copy.
- `editorial-panel` is used for hero, bundle, reviews, and any section that needs to feel like a campaign spread.
- `marquee-strip`/signal bars can repeat brand truths: **Salt as accessory · Bag-ready · Small-batch · Big flavour · You are the prize**.

## Do's and Don'ts

- **Do** make the site feel like a fashion accessory drop that happens to be edible.
- **Do** use oversized campaign headlines and tight all-caps utility labels.
- **Do** keep the three core flavors obvious: Spicy Citrus, Garlic Butter, Cinnamon Sugar.
- **Do** put the Trophy Set close to products as the clean upsell.
- **Don't** lean into rustic food, handwritten farmstand, beige wellness, or generic premium pantry tropes.
- **Don't** overuse soft rounded cards or emoji icons; use stickers, ribbons, and text marks instead.
- **Don't** let long body copy slow the purchase path. Pull the sharpest lines forward.
- **Don't** introduce a fourth flavor in live commerce copy unless the product actually exists.
