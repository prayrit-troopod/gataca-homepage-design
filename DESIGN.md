---
name: Gataca Homepage
description: Clean white wellness storefront. Soft grey cards, black pill CTAs, one deep blue feature, geometric sans. Photography and product bottles carry the colour.
colors:
  ink: "#0a0a0a"
  muted: "#3a3a3a"
  page: "#ffffff"
  card: "#f2f2f2"
  label: "#e6ddd3"
  dark: "#000000"
  blue: "#175e8c"
  hero-top: "#f3eadb"
  hero-bottom: "#9fb1ad"
typography:
  family: "Jost (stand-in for the mockup's geometric sans, e.g. Futura / Century Gothic)"
  weights: [400, 600]
  display: { mobile: "30-34px / 600 / -0.03em", desktop: "60px" }
  section-heading: { mobile: "26-28px / 400 with a 600 keyword", desktop: "48px" }
  card-title: { mobile: "15-17px / 600", desktop: "24px" }
  body: { mobile: "13-16px / 400", desktop: "18px" }
radii:
  card-lg: "28px mobile / 32px desktop"
  card-md: "20px mobile / 26px desktop"
  pill: "999px"
  label: "10-14px"
breakpoints:
  mobile: "< 768px (source design)"
  tablet: "768px+"
  desktop: "1024px+, content max-width 1680px, 20-40px side gutter"
---

# Gataca Homepage – design system

Source: `Website Draft.pdf` (mobile mockup). Built page: `index.html`. Shareable single file: `share/Gataca-Homepage-Design.html`.

## Visual theme
White page, generous spacing, soft `#f2f2f2` cards with large radii. The colour comes from the photos and the bottle labels, not from the UI. The only solid colour blocks are the black PM Stack card and the blue Standards card.

## Type
- One geometric sans throughout.
- Section headings mix weights: one keyword bold, the rest regular ("**Explore** by goal", "The **Gataca** Standards").
- Display and headings use tight tracking (-0.02 to -0.03em).

## Components
- **Nav bar**: a white rounded bar floating over the illustrated banner. Menu on the left; search and cart on the right.
- **Primary CTA**: a black pill with white text ("Shop Now").
- **Secondary CTA**: a white pill on grey cards, or an outlined rounded rectangle on the stack cards ("Explore").
- **Tag**: a small black pill in the card's top-left corner ("Bestseller", "Soldout").
- **Goal card**: a portrait photo with a beige `#e6ddd3` label across the bottom.
- **Testimonial card**: a portrait photo with a black handle tag in the top-left corner.
- **Product card**: grey card, centred title, star rating and review count (or a "New" chip), bottle, a scrollable USP list with check icons, white Shop Now pill, "Starting at" price. The Shop Now buttons line up across a row.
- **Stack cards**: AM is white with a soft shadow; PM is black. Each has an icon, a large light title, an Explore button and the product group.
- **FAQ item**: a grey rounded card with a bold question and a "+" in a white circle. When open, the circle turns black and the "+" rotates into an "×"; the answer sits below in muted text.
- **Blog card**: rounded photo, outlined read-time chip, bold title, excerpt, underlined Read More.
- **Footer**: a black rounded card (same black as the PM Stack card). GATACA wordmark, "**Subscribe** to our emails" with a dark pill email field and a white Subscribe pill, About, and Quick links in two columns, then the FDA disclaimer and copyright under a thin rule. Copy and links come from the gataca.in footer. The form is design-only: it shows a thank-you line and sends nothing.

## Menu
The hamburger opens a left drawer that mirrors the gataca.in mobile menu. It has GATACA, Shop, More and "What our customers say". Shop and More slide to their own panels with a back link, and Trans-Resveratrol has a third level. The footer holds the region picker and a black Account pill. The links point at the live gataca.in pages.

## Section order
1. Banner + nav
2. Hero
3. Explore by goal
4. Research Backed Supplements
5. #DoMore with Sam's Stacks
6. Testimonials
7. Our Goal
8. The Gataca Standards
9. Podcasts
10. Blog
11. FAQ ("For the avidly curious", copy from gataca.in)
12. Footer (copy and links from gataca.in)

## Desktop scaling rules
The content and order match the mobile design. Only the layout widens:
- **Banner and hero** run full-bleed, edge to edge. The nav bar and hero copy stay aligned with the page content.
- **Hero** splits in two: copy on the left, product shot on the right. The image fades in from the left.
- **Testimonials** work the same way as Explore by goal: larger cards in a peeking row, scrolled by the heading arrow.
- **Blog** matches mobile: heading on top, four posts in one row.
- **Footer** puts Subscribe, About and Quick links in three columns, with the disclaimer on the left and the copyright on the right of the bottom row.
- **FAQ** keeps its heading on top, with the questions in two fixed columns of five so opening one never moves the others.
- **Explore by goal** shows larger cards in a sideways row, about 4.3 visible so the next one peeks in, as on mobile. The heading arrow scrolls the row.
- **Products** sit in one row of four.
- **Sam's Stacks** keeps the mobile pieces and order. Sam is on the left, her head breaking out of the grey card. AM sits above PM on the right, each card turned landscape: icon, title and Explore on the left, products on the right. The two cards together match the height of Sam's grey card.
- **Our Goal** puts the photo on the left and the story on the right.
- **Standards and Podcasts** sit side by side. Both headings are on one line at the same height, and both cards are the same height. The hand creative shows uncropped, and the podcast thumbnail fills its card, trimmed slightly on the right.

## Do / don't
- Keep the UI neutral so the product and lifestyle photos stay the hero.
- Use black for actions; don't add accent-coloured buttons.
- Keep the mixed-weight headings; don't set whole headings in bold.
- Don't put text over the busy middle of photos. Labels sit in solid chips.

## Open items
- Four goal-card photos are temporary Pinterest placeholders until the brand sends its own creatives:
  - `goal-energy-focus.jpg`
  - `goal-sleep-recovery.jpg`
  - `goal-strength-performance.jpg`
  - `goal-heart-health.jpg`
- Four testimonial photos and their handles are placeholders (Pinterest images, `@customer_3` to `@customer_6`):
  - `testimonial-3.jpg` to `testimonial-6.jpg`
- Blog photos 2, 3 and 4 are Pinterest placeholders (`blog-2.jpg` to `blog-4.jpg`); posts 3 and 4 also have placeholder titles and excerpts.
- Replace the images with the original high-res photos. The crops come from a 333px-wide PDF.
- These blog and card images are only slivers in the mockup:
  - `goal-metabolism.jpg`
  - `testimonial-2.jpg`
- Some text is still baked into images:
  - the banner logo (now a high-res banner, logo is part of the artwork)
  - "Performance Matters"
  - the podcast thumbnail
