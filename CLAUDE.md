# The Chromatic Ascension site

This is the company's own website. Not a placeholder, not a form-field filler — the
public face of Eli's art practice, and the only page a stranger will find when they look
him up. It is maintained by the company.

Live at **https://snapwave333.github.io/chromatic-ascension/**
Repo: `Snapwave333/chromatic-ascension` (public, GitHub Pages from `master`, root).

## The rules that do not bend

1. **All artwork is original and made by hand by Eli Kenny.** Never describe any piece as
   AI-generated, AI-assisted, or generated. Never imply it. This is the same rule the
   clip business runs under and it is not negotiable here either.
2. **Never publish a claim that is not true.** No fake testimonials, no invented press,
   no "as seen in", no follower counts you have not verified, no products that do not
   exist yet described as available. A site that overstates is worse than a plain one,
   because the first thing a buyer checks is whether you were honest.
3. **Static HTML only.** No build step, no framework, no dependency tree. This page has
   to still work in three years with nobody maintaining it. Anything that needs `npm
   install` to render a paragraph is the wrong tool here.

## Deploying

```bash
cd C:/Users/chrom/src/chromatic-ascension-site
# edit index.html
git add -A && git commit -m "site: what changed" && git push
```

Pages rebuilds within about a minute. **Verify by fetching the live URL**, not by reading
the diff — a push that succeeds and a page that renders are different facts, and the one
that matters is what a visitor sees.

## What it is for

In priority order:

1. **Proving the work is real.** Someone who finds a listing wants to know a person made
   it. Show the art.
2. **Sending people to where they can buy.** Etsy listings and the Shopify store, once
   they are live.
3. **Backing the Etsy app registration.** The `Chromatic Ascension Listing Manager` app
   names this site as its website; the description here must keep matching what that tool
   actually does.

## Worth doing, in rough order of value

- **Show actual artwork.** The page currently describes the art without displaying any,
  which is the biggest gap. 159 pieces exist at
  `hermes/skills/mobile-apps/art-business/scripts/art_export/`. They are 1080px — fine
  for screen, and screen is what is being sold. Optimise them and lay out a small gallery;
  do not ship 92MB to a visitor's phone.
- **Link the shops** the moment listings are live.
- **Keep it fast.** No web fonts, no trackers, no analytics scripts. It loads instantly
  today and that is a feature worth defending.
- **Mobile first.** Most people who follow an art link are on a phone.

## What needs Eli

Publishing anything that speaks for him beyond plain description of the work: prices,
promises about delivery or turnaround, commission terms, or contact details other than
the Instagram already listed. Design, copy-editing, layout and performance are the
company's own call.
