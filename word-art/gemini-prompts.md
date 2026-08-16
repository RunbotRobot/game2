# LEXIQUEST word-art prompts for Gemini

237 words, split into 20 batches of up to 12. Each batch below is
one ready-to-paste prompt that asks for a grid image, same idea as the
companion-portrait / spirit-blob sheet you generated before. Send me
whatever comes back (paste it in chat, or upload to Drive and tell me) and
I'll crop, matte the background, and push each one to `word-art/<WORD>.png`.

**Changes from the first version of this list:**
- No more forced noun=blue/verb=red/adjective=green/adverb=purple. Each
  spirit uses whatever color best fits its own concept — that variety is
  the point, it makes each one more visually distinct and memorable.
- No more in-image text captions. Gemini's text rendering was showing up
  with inconsistent fonts/sizes/positions, which made panels harder to
  tell apart rather than easier. Instead, each prompt specifies an exact
  grid layout (columns × rows, filled left-to-right then top-to-bottom),
  and the numbered list below the prompt tells you and me which word is
  in which grid position — no rendered text needed in the artwork itself.
  (In the game, the word and its part of speech are already shown as an
  HTML/CSS label next to the art, so there was never a need for the image
  itself to carry that label.)

**Style anchor** (already baked into each batch prompt below, shown here
just for reference): cute chibi fantasy-spirit style matching the existing
game art — soft cel-shaded digital painting, big expressive eyes, simple
rounded body, transparent background, centered per panel.

This covers every word in `WORD_BANK` as of the commit that added this
file. As new words get added to the game later, append new batches here
rather than starting a separate list, so this stays the single source of
truth for "which words still need art."

---

## Batch 1 of 20 — ABANDON, ABUNDANT, ACCLAIM, AMPLIFY, ANCIENT, ANXIOUS, ASTONISH, BLEAK, BRITTLE, CANDID, CHRONIC, CONCEAL

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. ABANDON (verb) — a small creature dropping a bundle and walking away, looking back sadly.
2. ABUNDANT (adjective) — a spirit overflowing with fruit and coins spilling out around it.
3. ACCLAIM (noun) — a spirit surrounded by confetti and sparkles, arms raised in triumph.
4. AMPLIFY (verb) — a spirit shouting into a glowing megaphone with sound waves growing bigger.
5. ANCIENT (adjective) — a small mossy stone golem spirit covered in cracks and vines.
6. ANXIOUS (adjective) — a jittery spirit biting its nails with sweat drops and wide worried eyes.
7. ASTONISH (verb) — a spirit with eyes wide and mouth open, sparks of surprise around its head.
8. BLEAK (adjective) — a gray, wilted spirit standing in a barren, colorless landscape.
9. BRITTLE (adjective) — a thin glassy crystal spirit with visible cracks, looking fragile.
10. CANDID (adjective) — a spirit holding up a clear glass speech bubble, open honest expression.
11. CHRONIC (adjective) — a tired spirit wrapped in a blanket beside a repeating spiral clock symbol.
12. CONCEAL (verb) — a spirit peeking out from behind a curtain, half-hidden.
```

## Batch 2 of 20 — CONDEMN, CURIOUS, DECEIVE, DELICATE, DESOLATE, DILIGENT, ECLIPSE, ELOQUENT, EMBARK, ENDURE, ENIGMA, FAMISHED

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. CONDEMN (verb) — a stern spirit pointing a finger, a small glowing red gavel mark.
2. CURIOUS (adjective) — a spirit peering through a magnifying glass with sparkling curious eyes.
3. DECEIVE (verb) — a sly spirit with a mask, one hand behind its back with crossed fingers.
4. DELICATE (adjective) — a fragile lace-and-glass spirit carefully holding a soap bubble.
5. DESOLATE (adjective) — a lonely spirit standing in an empty windswept desert.
6. DILIGENT (adjective) — a spirit hard at work with tools, sleeves rolled up, focused expression.
7. ECLIPSE (noun) — a spirit shaped like a glowing crescent, half in shadow, ringed with light.
8. ELOQUENT (adjective) — a spirit mid-speech with musical notes and sparkling words flowing from its mouth.
9. EMBARK (verb) — a spirit stepping onto a tiny boat with a bundle, waving goodbye.
10. ENDURE (verb) — a spirit standing firm against wind and rain, gritting its teeth.
11. ENIGMA (noun) — a spirit wrapped in a swirling cloak patterned with question marks.
12. FAMISHED (adjective) — a spirit with a growling belly, eyeing a feast with huge hungry eyes.
```

## Batch 3 of 20 — FICKLE, FLOURISH, FRUGAL, GENUINE, GLIMMER, GRATEFUL, HUMBLE, IMMENSE, INTREPID, JUBILANT, KINDLE, LINGER

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. FICKLE (adjective) — a spirit split in two colors with a weathervane spinning above its head.
2. FLOURISH (verb) — a spirit blooming with flowers and leaves sprouting from its body.
3. FRUGAL (adjective) — a spirit carefully counting a single coin, wearing patched clothes.
4. GENUINE (adjective) — a spirit with a glowing heart symbol on its chest, warm honest smile.
5. GLIMMER (noun) — a tiny dim spirit made of one flickering spark of light in darkness.
6. GRATEFUL (adjective) — a spirit with hands clasped, sparkling tears of joy, heart-shaped glow.
7. HUMBLE (adjective) — a small, modestly dressed spirit bowing slightly with a gentle smile.
8. IMMENSE (adjective) — a spirit towering enormous beside a tiny house at its feet.
9. INTREPID (adjective) — a spirit in explorer gear holding a flag, standing atop a cliff.
10. JUBILANT (adjective) — a spirit leaping joyfully into the air amid confetti and streamers.
11. KINDLE (verb) — a spirit gently cupping a small newborn flame in its hands.
12. LINGER (verb) — a spirit slowly fading like mist, reluctant to leave a doorway.
```

## Batch 4 of 20 — LUMINOUS, MERIDIAN, MISCHIEF, OBSOLETE, OMINOUS, QUAINT, RADIANT, RECKLESS, SERENE, SKEPTIC, SOLITUDE, VIGILANT

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. LUMINOUS (adjective) — a spirit glowing brightly like a lantern, soft light radiating outward.
2. MERIDIAN (noun) — a spirit standing atop a mountain peak at high noon, sun directly overhead.
3. MISCHIEF (noun) — a grinning spirit mid-prank, hiding a whoopee cushion behind its back.
4. OBSOLETE (adjective) — a dusty spirit shaped like an old rotary phone, draped in cobwebs.
5. OMINOUS (adjective) — a shadowy spirit under dark storm clouds with glowing red eyes.
6. QUAINT (adjective) — a spirit shaped like a tiny cottage with flower boxes and a thatched roof.
7. RADIANT (adjective) — a spirit glowing like the sun with rays beaming outward.
8. RECKLESS (adjective) — a spirit skateboarding off a ramp with no helmet, wild grin.
9. SERENE (adjective) — a spirit meditating peacefully on a lily pad amid calm ripples.
10. SKEPTIC (noun) — a spirit with one eyebrow raised, arms crossed, a question mark overhead.
11. SOLITUDE (noun) — a spirit sitting alone under a single tree at dusk.
12. VIGILANT (adjective) — a spirit standing watch with a lantern, alert eyes scanning the dark.
```

## Batch 5 of 20 — VIVID, YEARN, ZEALOUS, QI, ZA, KA, OBI, YEW, ZED, NTH, QUOKKA, AXOLOTL

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. VIVID (adjective) — a spirit bursting with rainbow colors and swirling paint.
2. YEARN (verb) — a spirit reaching toward a distant glowing star, wistful expression.
3. ZEALOUS (adjective) — a spirit waving a banner energetically, fire in its eyes.
4. QI (noun) — a spirit made of swirling glowing energy lines around a calm center.
5. ZA (noun) — a spirit shaped like a cheerful slice of pizza.
6. KA (noun) — a spirit like a glowing ancient Egyptian statue with upraised arms.
7. OBI (noun) — a spirit wearing an elaborate kimono sash tied in a bow.
8. YEW (noun) — a spirit made of dark evergreen branches with red berries.
9. ZED (noun) — a spirit shaped like a glowing letter Z.
10. NTH (adjective) — a spirit standing at the end of an infinite receding staircase.
11. QUOKKA (noun) — a small smiling quokka creature spirit.
12. AXOLOTL (noun) — a pink axolotl creature spirit with feathery gills.
```

## Batch 6 of 20 — OKAPI, PANGOLIN, NARWHAL, DUGONG, WRASSE, STOAT, SHREW, LEMUR, CIVET, GECKO, IBEX, LYNX

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. OKAPI (noun) — an okapi creature spirit with zebra-striped legs.
2. PANGOLIN (noun) — a pangolin creature spirit curling into a scaly ball.
3. NARWHAL (noun) — a narwhal creature spirit with a spiral tusk amid arctic sparkles.
4. DUGONG (noun) — a dugong creature spirit floating in blue water.
5. WRASSE (noun) — a colorful wrasse fish spirit swimming among coral.
6. STOAT (noun) — a stoat creature spirit with a white winter coat and black-tipped tail.
7. SHREW (noun) — a tiny shrew creature spirit with a long twitching nose.
8. LEMUR (noun) — a ring-tailed lemur creature spirit.
9. CIVET (noun) — a civet creature spirit with a masked face.
10. GECKO (noun) — a gecko creature spirit clinging to a leaf with big round toes.
11. IBEX (noun) — an ibex creature spirit with huge curved horns.
12. LYNX (noun) — a lynx creature spirit with tufted ears.
```

## Batch 7 of 20 — NEWT, VOLE, WHELK, YAK, ZEBU, LICHEN, SEDGE, HEATHER, BRACKEN, THISTLE, NETTLE, YURT

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. NEWT (noun) — a newt creature spirit resting on a lily pad.
2. VOLE (noun) — a chubby vole creature spirit peeking from a grassy burrow.
3. WHELK (noun) — a whelk creature spirit peeking out of its spiral shell.
4. YAK (noun) — a shaggy yak creature spirit with long fur and curved horns.
5. ZEBU (noun) — a zebu creature spirit with a humped back.
6. LICHEN (noun) — a spirit made of textured lichen patches on stone, green and gray.
7. SEDGE (noun) — a spirit made of tall grassy blades growing by water.
8. HEATHER (noun) — a spirit covered in small purple heather blossoms.
9. BRACKEN (noun) — a spirit made of curling green fern fronds.
10. THISTLE (noun) — a spirit shaped like a spiky purple thistle flower.
11. NETTLE (noun) — a spirit made of jagged leaves with tiny warning sparks.
12. YURT (noun) — a spirit shaped like a round felt yurt tent with a peaked roof.
```

## Batch 8 of 20 — ABACUS, CAIRN, SCONCE, TRELLIS, GAZEBO, PARAPET, ALCOVE, ATRIUM, CORNICE, SCURRY, SKULK, LURCH

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. ABACUS (noun) — a spirit made from a wooden abacus frame with colorful beads.
2. CAIRN (noun) — a spirit made of stacked balancing stones.
3. SCONCE (noun) — a spirit shaped like a wall candle sconce with a flickering flame.
4. TRELLIS (noun) — a spirit made of a wooden lattice covered in climbing vines.
5. GAZEBO (noun) — a spirit shaped like a tiny garden gazebo draped in flowers.
6. PARAPET (noun) — a spirit shaped like a small stone castle wall with battlements.
7. ALCOVE (noun) — a spirit peeking out from a cozy recessed nook.
8. ATRIUM (noun) — a spirit standing in a sunlit glass-roofed courtyard.
9. CORNICE (noun) — a spirit shaped like ornate carved molding along a rooftop edge.
10. SCURRY (verb) — a spirit dashing on tiny fast legs, motion lines trailing behind.
11. SKULK (verb) — a spirit creeping low through shadows, sneaking.
12. LURCH (verb) — a spirit stumbling off-balance, mid-tumble.
```

## Batch 9 of 20 — WHITTLE, QUELL, QUAFF, QUIP, JOSTLE, KNEAD, MUSE, NESTLE, OGLE, PILFER, RAVEL, THWART

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. WHITTLE (verb) — a spirit carving a small wooden figure with a knife, shavings falling.
2. QUELL (verb) — a spirit raising a calming hand toward a small storm cloud.
3. QUAFF (verb) — a spirit gulping happily from a big mug, drink splashing.
4. QUIP (verb) — a spirit with a speech bubble containing a tiny star, sly grin.
5. JOSTLE (verb) — two small spirits bumping shoulders in a crowd.
6. KNEAD (verb) — a spirit pressing and folding a ball of dough, flour dust in the air.
7. MUSE (verb) — a spirit resting its chin on its hand, a swirling thought bubble above.
8. NESTLE (verb) — a spirit curled up cozily inside a soft nest.
9. OGLE (verb) — a spirit with wide cartoonish heart-shaped eyes staring.
10. PILFER (verb) — a sneaky spirit tiptoeing away with a small stolen trinket.
11. RAVEL (verb) — a spirit tangled up in a knot of yarn.
12. THWART (verb) — a spirit raising a small shield to block an incoming arrow.
```

## Batch 10 of 20 — VEER, WANE, USURP, VANQUISH, WHET, YOKE, BADGER, DAWDLE, FESTER, GRAPPLE, HOARD, IMPUGN

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. VEER (verb) — a spirit swerving sharply to one side with a motion trail.
2. WANE (verb) — a spirit fading from bright to dim like a shrinking moon.
3. USURP (verb) — a small spirit sneakily lifting a crown off another's head.
4. VANQUISH (verb) — a triumphant spirit standing over a defeated shadow foe.
5. WHET (verb) — a spirit sharpening a blade on a whetstone, sparks flying.
6. YOKE (verb) — two small spirits joined by a wooden yoke, working together.
7. BADGER (verb) — a spirit tugging insistently on another's sleeve, pestering.
8. DAWDLE (verb) — a spirit strolling slowly, distracted by a passing butterfly.
9. FESTER (verb) — a small spirit with a droopy wilting expression under a dark little cloud.
10. GRAPPLE (verb) — a spirit wrestling with a tangled length of rope.
11. HOARD (verb) — a spirit sitting atop a huge pile of shiny coins and gems.
12. IMPUGN (verb) — a spirit pointing accusingly with a skeptical raised eyebrow.
```

## Batch 11 of 20 — JEER, LAMENT, MOLLIFY, NULLIFY, TACITURN, INDOLENT, MYRIAD, NEBULOUS, OPAQUE, RAUCOUS, SANGUINE, TORPID

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. JEER (verb) — a spirit cupping its hands around its mouth, shouting mockingly.
2. LAMENT (verb) — a spirit with drooping shoulders and a single sparkling tear.
3. MOLLIFY (verb) — a gentle spirit patting another spirit's back soothingly.
4. NULLIFY (verb) — a spirit striking a glowing X through a magic contract.
5. TACITURN (adjective) — a quiet spirit with sealed lips, arms folded, saying nothing.
6. INDOLENT (adjective) — a spirit lazily lounging in a hammock, eyes half-closed.
7. MYRIAD (adjective) — a spirit surrounded by countless tiny sparkling stars.
8. NEBULOUS (adjective) — a soft, foggy, indistinct cloud-shaped spirit.
9. OPAQUE (adjective) — a spirit made of frosted, cloudy glass you can't see through.
10. RAUCOUS (adjective) — a spirit shouting loudly with jagged sound-wave lines.
11. SANGUINE (adjective) — a spirit smiling confidently in front of a bright sunrise.
12. TORPID (adjective) — a sleepy spirit slumped over, barely awake, drooping eyelids.
```

## Batch 12 of 20 — UNCTUOUS, VAPID, WISTFUL, ZESTY, PARADOX, OXYMORON, EUPHORIA, MALAISE, QUANDARY, RESPITE, SOLACE, TUMULT

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. UNCTUOUS (adjective) — an overly-smiling, oily-looking spirit bowing with exaggerated flattery.
2. VAPID (adjective) — a plain, blank-faced spirit with an empty speech bubble.
3. WISTFUL (adjective) — a spirit gazing at a sunset with a soft, longing smile.
4. ZESTY (adjective) — a spirit shaped like a citrus slice, bursting with juicy sparkle.
5. PARADOX (noun) — a spirit split in two, each half pulling opposite ways around an infinity loop.
6. OXYMORON (noun) — a spirit that is half fire, half ice, in one small body.
7. EUPHORIA (noun) — a spirit soaring joyfully through the air trailing radiant light.
8. MALAISE (noun) — a droopy, pale spirit slumped under a small gray cloud.
9. QUANDARY (noun) — a spirit standing at a fork in the road, scratching its head.
10. RESPITE (noun) — a spirit resting in a hammock in dappled shade, sighing contentedly.
11. SOLACE (noun) — a spirit wrapped gently in a warm glowing blanket.
12. TUMULT (noun) — a spirit caught in the middle of a swirling chaotic crowd of shapes.
```

## Batch 13 of 20 — VORTEX, ZENITH, NADIR, FACADE, INSOMNIA, JARGON, KINSHIP, AA, AB, AD, AE, AG

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. VORTEX (noun) — a spirit at the center of a swirling spiral of wind.
2. ZENITH (noun) — a spirit standing triumphantly at the very top of a mountain peak.
3. NADIR (noun) — a spirit sitting at the bottom of a deep dark pit, a small light far above.
4. FACADE (noun) — a spirit holding up a painted mask in front of its own face.
5. INSOMNIA (noun) — a wide-eyed spirit lying in bed under a starry night sky, unable to sleep.
6. JARGON (noun) — a spirit surrounded by floating gears and technical symbols, one confused onlooker.
7. KINSHIP (noun) — two small spirits holding hands, matching glowing hearts.
8. AA (noun) — a spirit made of jagged black volcanic rock with glowing lava cracks.
9. AB (noun) — a small muscular spirit flexing its abdominal muscles proudly.
10. AD (noun) — a spirit holding up a tiny glowing billboard sign.
11. AE (adjective) — a spirit holding up a single glowing numeral one.
12. AG (noun) — a spirit wearing a straw hat, holding a sprouting wheat stalk.
```

## Batch 14 of 20 — AH, AI, AL, AM, AR, AS, AX, AY, BA, BI, BO, BY

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. AH (verb) — a spirit with mouth open in a delighted, surprised expression, sparkles around it.
2. AI (noun) — a sleepy three-toed sloth creature spirit hanging from a branch.
3. AL (noun) — a spirit grown from a red-dye tree, dripping crimson sap.
4. AM (verb) — a spirit forming from a puff of glowing smoke, mid-existence.
5. AR (noun) — a spirit shaped like a glowing letter R.
6. AS (adverb) — a spirit holding up a balance scale with two equal weights.
7. AX (verb) — a lumberjack spirit mid-swing with a small axe, wood chips flying.
8. AY (noun) — a spirit holding a ballot marked with a checkmark, cheering.
9. BA (noun) — a spirit shaped like an Egyptian ba-bird with a small human face.
10. BI (noun) — a spirit glowing in two blended colors side by side.
11. BO (noun) — a spirit giving a friendly wave and thumbs up.
12. BY (noun) — a spirit relaxing on a bench while others race past in a blur.
```

## Batch 15 of 20 — DA, DO, ED, EF, EL, EM, EN, ES, ET, EX, FA, GI

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. DA (noun) — a warm fatherly spirit holding a smaller spirit's hand.
2. DO (verb) — a determined spirit rolling up its sleeves, ready for action.
3. ED (noun) — a spirit holding a book and wearing a tiny graduation cap.
4. EF (noun) — a spirit shaped like a glowing letter F.
5. EL (noun) — a spirit riding happily on a tiny elevated train car.
6. EM (noun) — a spirit shaped like a glowing letter M holding a tiny ruler.
7. EN (noun) — a spirit shaped like a glowing letter N, a little smaller than its cousin EM.
8. ES (noun) — a spirit shaped like a glowing letter S.
9. ET (verb) — an old-fashioned spirit happily munching on an apple.
10. EX (verb) — a spirit dragging a big red X mark across a page.
11. FA (noun) — a singing spirit with a musical note floating from its mouth.
12. GI (noun) — a small spirit dressed in a white martial-arts uniform with a belt.
```

## Batch 16 of 20 — GO, HA, ID, IF, JO, KI, LA, LI, MA, ME, MI, MO

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. GO (verb) — a spirit mid-run, dashing forward energetically.
2. HA (noun) — a laughing spirit doubled over with joy.
3. ID (noun) — a shadowy, instinct-driven spirit with wild untamed eyes.
4. IF (noun) — a spirit standing before two glowing branching paths.
5. JO (noun) — a spirit holding a small heart, blushing sweetly.
6. KI (noun) — a spirit glowing with swirling inner energy in a martial-arts stance.
7. LA (noun) — a singing spirit mid-song with a musical note beside it.
8. LI (noun) — a spirit walking a very long winding road, measuring the distance.
9. MA (noun) — a warm motherly spirit cradling a smaller spirit.
10. ME (noun) — a spirit looking thoughtfully at its own reflection in a small mirror.
11. MI (noun) — a singing spirit with a cheerful musical note.
12. MO (noun) — a spirit glancing at a pocket watch with a 'just a moment' gesture.
```

## Batch 17 of 20 — MU, NE, NO, NU, OD, OE, OH, OK, OM, ON, OP, OR

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. MU (noun) — a spirit shaped like the glowing Greek letter mu.
2. NE (adjective) — a spirit proudly holding up a family crest nameplate.
3. NO (noun) — a spirit crossing its arms in an X, shaking its head.
4. NU (noun) — a spirit shaped like the glowing Greek letter nu.
5. OD (noun) — a spirit radiating a mysterious invisible aura of energy.
6. OE (noun) — a small whirlwind spirit swirling over icy northern waters.
7. OH (verb) — a spirit with wide eyes and an open mouth in sudden realization.
8. OK (adjective) — a spirit giving a cheerful thumbs-up.
9. OM (noun) — a meditating spirit glowing with a soft sound-wave aura.
10. ON (noun) — a spirit standing ready in a cricket batting stance.
11. OP (noun) — a spirit made of swirling black-and-white optical-illusion patterns.
12. OR (noun) — a spirit shimmering in heraldic gold, shield-shaped.
```

## Batch 18 of 20 — OS, OX, PA, PE, PI, PO, RE, SI, SO, TA, TE, TI

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. OS (noun) — a small spirit made of a single glowing bone shape.
2. OX (noun) — a strong ox creature spirit pulling a small cart.
3. PA (noun) — a warm fatherly spirit ruffling a smaller spirit's hair.
4. PE (noun) — a spirit shaped like a glowing Hebrew letter pe.
5. PI (noun) — a spirit shaped like the glowing Greek letter pi with a circle motif.
6. PO (noun) — a small round spirit shaped like a chamber pot, sitting sheepishly.
7. RE (noun) — a singing spirit with a musical note, mid-scale.
8. SI (noun) — a singing spirit with a musical note.
9. SO (noun) — a singing spirit with a musical note, mid-melody.
10. TA (noun) — a spirit bowing gratefully amid sparkling thank-you hearts.
11. TE (noun) — a singing spirit with a musical note.
12. TI (noun) — a singing spirit reaching a high musical note.
```

## Batch 19 of 20 — UM, UP, UT, WO, YA, CWM, GNU, JEU, KOI, LEI, NIB, ORB

```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. UM (verb) — a spirit scratching its head with a hesitant thought bubble of dots.
2. UP (verb) — a spirit lifting a glowing arrow that points upward.
3. UT (noun) — an old-fashioned singing spirit with an antique musical note.
4. WO (noun) — a sorrowful, archaic spirit with a single weary teardrop.
5. YA (noun) — a spirit happily biting into a juicy round Asian pear.
6. CWM (noun) — a spirit nestled in a glacier-carved mountain bowl.
7. GNU (noun) — a gnu wildebeest creature spirit.
8. JEU (noun) — a playful spirit juggling glowing wordplay symbols.
9. KOI (noun) — a koi fish creature spirit swimming in a slow circle.
10. LEI (noun) — a spirit wearing a colorful flower garland necklace.
11. NIB (noun) — a spirit shaped like a fountain pen nib, dripping a bead of ink.
12. ORB (noun) — a spirit made of a glowing crystal sphere.
```

## Batch 20 of 20 — PYX, QAT, TSK, URN, VOX, WOK, YEP, ZEK, AVO

```
Create one image: a grid of 9 square panels, arranged in 4 columns, 2 full rows plus a final row of just 1 panel (left-aligned), filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. PYX (noun) — a spirit shaped like a small ornate golden box.
2. QAT (noun) — a spirit made of leafy green shrub branches.
3. TSK (verb) — a disapproving spirit wagging a finger, tongue mid-click.
4. URN (noun) — a spirit shaped like an ornate footed urn vase.
5. VOX (noun) — a spirit made of a glowing megaphone with a voice waveform.
6. WOK (noun) — a spirit shaped like a sizzling wok pan with veggies flying.
7. YEP (adverb) — a spirit giving an enthusiastic nod and thumbs up.
8. ZEK (noun) — a weary, thin spirit wrapped in a tattered gray coat, breath frosting the air.
9. AVO (noun) — a spirit holding up a small shiny coin.
```

