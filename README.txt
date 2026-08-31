ZUNIA — BRAND ASSET PACK
Version 1.0 · August 2026
Full guidelines: "Zunia Brand Book" in the project.

--------------------------------------------------------------------
THE MARK
--------------------------------------------------------------------
Two rules hold the top and bottom of a Z. The diagonal is never
drawn: two nodes sit on it, at one third and two thirds of its
length. Built on a 64 x 64 unit grid.

  Primary cut   rule stroke 9, nodes r 5.2 — use at 32 px and up
  Small cut     rule stroke 10, nodes r 6  — use at 16 to 31 px
  Contained     knocked out of a solid tile — app icons, favicon

Clear space  2x on every side, where x is the rule width.
Minimum      mark 24 px · lock-up 104 px wide · print 12 mm wide.
Lock-up      gap between mark and wordmark is fixed at 2x.
Wordmark     Space Grotesk Medium 500, lowercase, -0.055em tracking.
             Never re-space, re-set in another face, or capitalise.

--------------------------------------------------------------------
COLOUR
--------------------------------------------------------------------
Cobalt Ink    #10214F   RGB 16 33 79      CMYK 80 58 0 69
Paper         #F4F5F7   RGB 244 245 247   CMYK 1 1 0 3
Live Cobalt   #2050C4   RGB 32 80 196     CMYK 84 59 0 23
Near-black    #101012   RGB 16 16 18      CMYK 11 11 0 93

Support: Slate #4A5468 · Grey #6E7280 · Hairline #C7D2EA · Wash #E4E9F4
Proportion: 58% paper, 28% ink, 9% live cobalt, 5% wash.
There is no third brand colour and no gradient, ever.

--------------------------------------------------------------------
TYPE
--------------------------------------------------------------------
Space Grotesk  300 / 400 / 500 / 700 — wordmark, headings, UI, body
JetBrains Mono 400 / 500 — addresses, hashes, amounts, chain IDs,
                           labels and specification captions
Both are open source (SIL Open Font License), on Google Fonts.

--------------------------------------------------------------------
CONTENTS
--------------------------------------------------------------------
svg/     Vector masters. Marks, small cut, lock-ups, app tiles,
         favicon, profile circle, rule field tiles, and three
         animated (CSS) versions of the logo loop.
         Lock-up SVGs pull Space Grotesk from Google Fonts; convert
         the text to outlines before sending to a printer.

png/icons/    App and favicon tile: 16, 32, 48, 64, 128, 256, 512,
              1024 px, in ink and in cobalt.
png/mark/     Mark on transparent, ink / paper / near-black,
              512 to 2048 px wide.
png/lockup/   FULL LOGO — mark + wordmark, seven files:
                horizontal ink 2048 (transparent background)
                horizontal reversed 2048 (on ink)
                horizontal near-black mono 2048 (transparent)
                horizontal cobalt 2048 (transparent)
                horizontal white on cobalt 2048
                stacked ink 1400 (transparent)
                stacked reversed 1400 (on ink)
              Vector equivalents: svg/zunia-lockup-*.svg
png/social/   x-cover 1500x500 · linkedin-cover 1584x396 ·
              three 1080x1080 post templates · profile 256/512/1024.
png/pattern/  Rule field, light and dark, 1400 px seamless.
jpg/          The social assets and the horizontal lock-up, flattened
              on white, for systems that reject transparency.
gif/          Seamless 24-frame logo loop, 240 px, light and dark.
ico/          favicon.ico — 16, 32, 48, 64 px in one file.

--------------------------------------------------------------------
NOT IN THIS PACK
--------------------------------------------------------------------
MP4 / WebM   The loop is provided as GIF and as animated SVG.
             For video, screen-record the SVG or re-time the GIF.
EPS          Use the SVGs; any vector editor exports EPS or PDF
             from them without loss.

--------------------------------------------------------------------
NEVER
--------------------------------------------------------------------
Stretch, squash or rotate the mark. Add a diagonal, an outline, or
any part. Apply a gradient, shadow or glow. Recolour outside the
palette. Place it on a low-contrast ground or over pattern. Set the
wordmark in another face, in capitals, or at different tracking.
