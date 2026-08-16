# LEXIQUEST word-art prompts for Gemini

237 words, split into 20 batches of up to 12. For each batch there
are two blocks: **Paste to Gemini** (copy that whole thing, nothing else)
and **Reference key** (for you and me only - do not paste it). Send back
whatever Gemini generates and I'll crop, matte, and push each one to
`word-art/<WORD>.png`, matching crops to words by grid position using the
reference key.

**Changes from earlier versions of this list:**
- The word itself is no longer in the prompt at all - confirmed (batch 1,
  tested manually) that even with "no text" instructions, Gemini would
  sometimes render the word as a label if it appeared anywhere in the
  prompt text. Panels are identified purely by grid position now; the
  reference key underneath each prompt maps position -> word for us.
- No more forced noun=blue/verb=red/adjective=green/adverb=purple. Each
  spirit uses whatever color best fits its own concept - that variety is
  the point, it makes each one more visually distinct and memorable.
- (In the game, the word and its part of speech are already shown as an
  HTML/CSS label next to the art, so the image itself never needed to
  carry that label anyway.)

**Style anchor** (already baked into each prompt below, shown here just
for reference): cute chibi fantasy-spirit style matching the existing
game art - soft cel-shaded digital painting, big expressive eyes, simple
rounded body, transparent background, centered per panel.

This covers every word in `WORD_BANK` as of the commit that added this
file. As new words get added to the game later, append new batches here
rather than starting a separate list, so this stays the single source of
truth for "which words still need art."

---

## Batch 1 of 20 — ABANDON, ABUNDANT, ACCLAIM, AMPLIFY, ANCIENT, ANXIOUS, ASTONISH, BLEAK, BRITTLE, CANDID, CHRONIC, CONCEAL

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a small creature dropping a bundle and walking away, looking back sadly.
2. a spirit overflowing with fruit and coins spilling out around it.
3. a spirit surrounded by confetti and sparkles, arms raised in triumph.
4. a spirit shouting into a glowing megaphone with sound waves growing bigger.
5. a small mossy stone golem spirit covered in cracks and vines.
6. a jittery spirit biting its nails with sweat drops and wide worried eyes.
7. a spirit with eyes wide and mouth open, sparks of surprise around its head.
8. a gray, wilted spirit standing in a barren, colorless landscape.
9. a thin glassy crystal spirit with visible cracks, looking fragile.
10. a spirit holding up a clear glass speech bubble, open honest expression.
11. a tired spirit wrapped in a blanket beside a repeating spiral clock symbol.
12. a spirit peeking out from behind a curtain, half-hidden.
```

**Reference key** (not part of the prompt):
1. ABANDON (verb)
2. ABUNDANT (adjective)
3. ACCLAIM (noun)
4. AMPLIFY (verb)
5. ANCIENT (adjective)
6. ANXIOUS (adjective)
7. ASTONISH (verb)
8. BLEAK (adjective)
9. BRITTLE (adjective)
10. CANDID (adjective)
11. CHRONIC (adjective)
12. CONCEAL (verb)

## Batch 2 of 20 — CONDEMN, CURIOUS, DECEIVE, DELICATE, DESOLATE, DILIGENT, ECLIPSE, ELOQUENT, EMBARK, ENDURE, ENIGMA, FAMISHED

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a stern spirit pointing a finger, a small glowing red gavel mark.
2. a spirit peering through a magnifying glass with sparkling curious eyes.
3. a sly spirit with a mask, one hand behind its back with crossed fingers.
4. a fragile lace-and-glass spirit carefully holding a soap bubble.
5. a lonely spirit standing in an empty windswept desert.
6. a spirit hard at work with tools, sleeves rolled up, focused expression.
7. a spirit shaped like a glowing crescent, half in shadow, ringed with light.
8. a spirit mid-speech with musical notes and sparkling words flowing from its mouth.
9. a spirit stepping onto a tiny boat with a bundle, waving goodbye.
10. a spirit standing firm against wind and rain, gritting its teeth.
11. a spirit wrapped in a swirling cloak patterned with question marks.
12. a spirit with a growling belly, eyeing a feast with huge hungry eyes.
```

**Reference key** (not part of the prompt):
1. CONDEMN (verb)
2. CURIOUS (adjective)
3. DECEIVE (verb)
4. DELICATE (adjective)
5. DESOLATE (adjective)
6. DILIGENT (adjective)
7. ECLIPSE (noun)
8. ELOQUENT (adjective)
9. EMBARK (verb)
10. ENDURE (verb)
11. ENIGMA (noun)
12. FAMISHED (adjective)

## Batch 3 of 20 — FICKLE, FLOURISH, FRUGAL, GENUINE, GLIMMER, GRATEFUL, HUMBLE, IMMENSE, INTREPID, JUBILANT, KINDLE, LINGER

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit split in two colors with a weathervane spinning above its head.
2. a spirit blooming with flowers and leaves sprouting from its body.
3. a spirit carefully counting a single coin, wearing patched clothes.
4. a spirit with a glowing heart symbol on its chest, warm honest smile.
5. a tiny dim spirit made of one flickering spark of light in darkness.
6. a spirit with hands clasped, sparkling tears of joy, heart-shaped glow.
7. a small, modestly dressed spirit bowing slightly with a gentle smile.
8. a spirit towering enormous beside a tiny house at its feet.
9. a spirit in explorer gear holding a flag, standing atop a cliff.
10. a spirit leaping joyfully into the air amid confetti and streamers.
11. a spirit gently cupping a small newborn flame in its hands.
12. a spirit slowly fading like mist, reluctant to leave a doorway.
```

**Reference key** (not part of the prompt):
1. FICKLE (adjective)
2. FLOURISH (verb)
3. FRUGAL (adjective)
4. GENUINE (adjective)
5. GLIMMER (noun)
6. GRATEFUL (adjective)
7. HUMBLE (adjective)
8. IMMENSE (adjective)
9. INTREPID (adjective)
10. JUBILANT (adjective)
11. KINDLE (verb)
12. LINGER (verb)

## Batch 4 of 20 — LUMINOUS, MERIDIAN, MISCHIEF, OBSOLETE, OMINOUS, QUAINT, RADIANT, RECKLESS, SERENE, SKEPTIC, SOLITUDE, VIGILANT

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit glowing brightly like a lantern, soft light radiating outward.
2. a spirit standing atop a mountain peak at high noon, sun directly overhead.
3. a grinning spirit mid-prank, hiding a whoopee cushion behind its back.
4. a dusty spirit shaped like an old rotary phone, draped in cobwebs.
5. a shadowy spirit under dark storm clouds with glowing red eyes.
6. a spirit shaped like a tiny cottage with flower boxes and a thatched roof.
7. a spirit glowing like the sun with rays beaming outward.
8. a spirit skateboarding off a ramp with no helmet, wild grin.
9. a spirit meditating peacefully on a lily pad amid calm ripples.
10. a spirit with one eyebrow raised, arms crossed, a question mark overhead.
11. a spirit sitting alone under a single tree at dusk.
12. a spirit standing watch with a lantern, alert eyes scanning the dark.
```

**Reference key** (not part of the prompt):
1. LUMINOUS (adjective)
2. MERIDIAN (noun)
3. MISCHIEF (noun)
4. OBSOLETE (adjective)
5. OMINOUS (adjective)
6. QUAINT (adjective)
7. RADIANT (adjective)
8. RECKLESS (adjective)
9. SERENE (adjective)
10. SKEPTIC (noun)
11. SOLITUDE (noun)
12. VIGILANT (adjective)

## Batch 5 of 20 — VIVID, YEARN, ZEALOUS, QI, ZA, KA, OBI, YEW, ZED, NTH, QUOKKA, AXOLOTL

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit bursting with rainbow colors and swirling paint.
2. a spirit reaching toward a distant glowing star, wistful expression.
3. a spirit waving a banner energetically, fire in its eyes.
4. a spirit made of swirling glowing energy lines around a calm center.
5. a spirit shaped like a cheerful slice of pizza.
6. a spirit like a glowing ancient Egyptian statue with upraised arms.
7. a spirit wearing an elaborate kimono sash tied in a bow.
8. a spirit made of dark evergreen branches with red berries.
9. a spirit shaped like a glowing letter Z.
10. a spirit standing at the end of an infinite receding staircase.
11. a small smiling quokka creature spirit.
12. a pink axolotl creature spirit with feathery gills.
```

**Reference key** (not part of the prompt):
1. VIVID (adjective)
2. YEARN (verb)
3. ZEALOUS (adjective)
4. QI (noun)
5. ZA (noun)
6. KA (noun)
7. OBI (noun)
8. YEW (noun)
9. ZED (noun)
10. NTH (adjective)
11. QUOKKA (noun)
12. AXOLOTL (noun)

## Batch 6 of 20 — OKAPI, PANGOLIN, NARWHAL, DUGONG, WRASSE, STOAT, SHREW, LEMUR, CIVET, GECKO, IBEX, LYNX

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. an okapi creature spirit with zebra-striped legs.
2. a pangolin creature spirit curling into a scaly ball.
3. a narwhal creature spirit with a spiral tusk amid arctic sparkles.
4. a dugong creature spirit floating in blue water.
5. a colorful wrasse fish spirit swimming among coral.
6. a stoat creature spirit with a white winter coat and black-tipped tail.
7. a tiny shrew creature spirit with a long twitching nose.
8. a ring-tailed lemur creature spirit.
9. a civet creature spirit with a masked face.
10. a gecko creature spirit clinging to a leaf with big round toes.
11. an ibex creature spirit with huge curved horns.
12. a lynx creature spirit with tufted ears.
```

**Reference key** (not part of the prompt):
1. OKAPI (noun)
2. PANGOLIN (noun)
3. NARWHAL (noun)
4. DUGONG (noun)
5. WRASSE (noun)
6. STOAT (noun)
7. SHREW (noun)
8. LEMUR (noun)
9. CIVET (noun)
10. GECKO (noun)
11. IBEX (noun)
12. LYNX (noun)

## Batch 7 of 20 — NEWT, VOLE, WHELK, YAK, ZEBU, LICHEN, SEDGE, HEATHER, BRACKEN, THISTLE, NETTLE, YURT

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a newt creature spirit resting on a lily pad.
2. a chubby vole creature spirit peeking from a grassy burrow.
3. a whelk creature spirit peeking out of its spiral shell.
4. a shaggy yak creature spirit with long fur and curved horns.
5. a zebu creature spirit with a humped back.
6. a spirit made of textured lichen patches on stone, green and gray.
7. a spirit made of tall grassy blades growing by water.
8. a spirit covered in small purple heather blossoms.
9. a spirit made of curling green fern fronds.
10. a spirit shaped like a spiky purple thistle flower.
11. a spirit made of jagged leaves with tiny warning sparks.
12. a spirit shaped like a round felt yurt tent with a peaked roof.
```

**Reference key** (not part of the prompt):
1. NEWT (noun)
2. VOLE (noun)
3. WHELK (noun)
4. YAK (noun)
5. ZEBU (noun)
6. LICHEN (noun)
7. SEDGE (noun)
8. HEATHER (noun)
9. BRACKEN (noun)
10. THISTLE (noun)
11. NETTLE (noun)
12. YURT (noun)

## Batch 8 of 20 — ABACUS, CAIRN, SCONCE, TRELLIS, GAZEBO, PARAPET, ALCOVE, ATRIUM, CORNICE, SCURRY, SKULK, LURCH

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit made from a wooden abacus frame with colorful beads.
2. a spirit made of stacked balancing stones.
3. a spirit shaped like a wall candle sconce with a flickering flame.
4. a spirit made of a wooden lattice covered in climbing vines.
5. a spirit shaped like a tiny garden gazebo draped in flowers.
6. a spirit shaped like a small stone castle wall with battlements.
7. a spirit peeking out from a cozy recessed nook.
8. a spirit standing in a sunlit glass-roofed courtyard.
9. a spirit shaped like ornate carved molding along a rooftop edge.
10. a spirit dashing on tiny fast legs, motion lines trailing behind.
11. a spirit creeping low through shadows, sneaking.
12. a spirit stumbling off-balance, mid-tumble.
```

**Reference key** (not part of the prompt):
1. ABACUS (noun)
2. CAIRN (noun)
3. SCONCE (noun)
4. TRELLIS (noun)
5. GAZEBO (noun)
6. PARAPET (noun)
7. ALCOVE (noun)
8. ATRIUM (noun)
9. CORNICE (noun)
10. SCURRY (verb)
11. SKULK (verb)
12. LURCH (verb)

## Batch 9 of 20 — WHITTLE, QUELL, QUAFF, QUIP, JOSTLE, KNEAD, MUSE, NESTLE, OGLE, PILFER, RAVEL, THWART

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit carving a small wooden figure with a knife, shavings falling.
2. a spirit raising a calming hand toward a small storm cloud.
3. a spirit gulping happily from a big mug, drink splashing.
4. a spirit with a speech bubble containing a tiny star, sly grin.
5. two small spirits bumping shoulders in a crowd.
6. a spirit pressing and folding a ball of dough, flour dust in the air.
7. a spirit resting its chin on its hand, a swirling thought bubble above.
8. a spirit curled up cozily inside a soft nest.
9. a spirit with wide cartoonish heart-shaped eyes staring.
10. a sneaky spirit tiptoeing away with a small stolen trinket.
11. a spirit tangled up in a knot of yarn.
12. a spirit raising a small shield to block an incoming arrow.
```

**Reference key** (not part of the prompt):
1. WHITTLE (verb)
2. QUELL (verb)
3. QUAFF (verb)
4. QUIP (verb)
5. JOSTLE (verb)
6. KNEAD (verb)
7. MUSE (verb)
8. NESTLE (verb)
9. OGLE (verb)
10. PILFER (verb)
11. RAVEL (verb)
12. THWART (verb)

## Batch 10 of 20 — VEER, WANE, USURP, VANQUISH, WHET, YOKE, BADGER, DAWDLE, FESTER, GRAPPLE, HOARD, IMPUGN

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit swerving sharply to one side with a motion trail.
2. a spirit fading from bright to dim like a shrinking moon.
3. a small spirit sneakily lifting a crown off another's head.
4. a triumphant spirit standing over a defeated shadow foe.
5. a spirit sharpening a blade on a whetstone, sparks flying.
6. two small spirits joined by a wooden yoke, working together.
7. a spirit tugging insistently on another's sleeve, pestering.
8. a spirit strolling slowly, distracted by a passing butterfly.
9. a small spirit with a droopy wilting expression under a dark little cloud.
10. a spirit wrestling with a tangled length of rope.
11. a spirit sitting atop a huge pile of shiny coins and gems.
12. a spirit pointing accusingly with a skeptical raised eyebrow.
```

**Reference key** (not part of the prompt):
1. VEER (verb)
2. WANE (verb)
3. USURP (verb)
4. VANQUISH (verb)
5. WHET (verb)
6. YOKE (verb)
7. BADGER (verb)
8. DAWDLE (verb)
9. FESTER (verb)
10. GRAPPLE (verb)
11. HOARD (verb)
12. IMPUGN (verb)

## Batch 11 of 20 — JEER, LAMENT, MOLLIFY, NULLIFY, TACITURN, INDOLENT, MYRIAD, NEBULOUS, OPAQUE, RAUCOUS, SANGUINE, TORPID

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit cupping its hands around its mouth, shouting mockingly.
2. a spirit with drooping shoulders and a single sparkling tear.
3. a gentle spirit patting another spirit's back soothingly.
4. a spirit striking a glowing X through a magic contract.
5. a quiet spirit with sealed lips, arms folded, saying nothing.
6. a spirit lazily lounging in a hammock, eyes half-closed.
7. a spirit surrounded by countless tiny sparkling stars.
8. a soft, foggy, indistinct cloud-shaped spirit.
9. a spirit made of frosted, cloudy glass you can't see through.
10. a spirit shouting loudly with jagged sound-wave lines.
11. a spirit smiling confidently in front of a bright sunrise.
12. a sleepy spirit slumped over, barely awake, drooping eyelids.
```

**Reference key** (not part of the prompt):
1. JEER (verb)
2. LAMENT (verb)
3. MOLLIFY (verb)
4. NULLIFY (verb)
5. TACITURN (adjective)
6. INDOLENT (adjective)
7. MYRIAD (adjective)
8. NEBULOUS (adjective)
9. OPAQUE (adjective)
10. RAUCOUS (adjective)
11. SANGUINE (adjective)
12. TORPID (adjective)

## Batch 12 of 20 — UNCTUOUS, VAPID, WISTFUL, ZESTY, PARADOX, OXYMORON, EUPHORIA, MALAISE, QUANDARY, RESPITE, SOLACE, TUMULT

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. an overly-smiling, oily-looking spirit bowing with exaggerated flattery.
2. a plain, blank-faced spirit with an empty speech bubble.
3. a spirit gazing at a sunset with a soft, longing smile.
4. a spirit shaped like a citrus slice, bursting with juicy sparkle.
5. a spirit split in two, each half pulling opposite ways around an infinity loop.
6. a spirit that is half fire, half ice, in one small body.
7. a spirit soaring joyfully through the air trailing radiant light.
8. a droopy, pale spirit slumped under a small gray cloud.
9. a spirit standing at a fork in the road, scratching its head.
10. a spirit resting in a hammock in dappled shade, sighing contentedly.
11. a spirit wrapped gently in a warm glowing blanket.
12. a spirit caught in the middle of a swirling chaotic crowd of shapes.
```

**Reference key** (not part of the prompt):
1. UNCTUOUS (adjective)
2. VAPID (adjective)
3. WISTFUL (adjective)
4. ZESTY (adjective)
5. PARADOX (noun)
6. OXYMORON (noun)
7. EUPHORIA (noun)
8. MALAISE (noun)
9. QUANDARY (noun)
10. RESPITE (noun)
11. SOLACE (noun)
12. TUMULT (noun)

## Batch 13 of 20 — VORTEX, ZENITH, NADIR, FACADE, INSOMNIA, JARGON, KINSHIP, AA, AB, AD, AE, AG

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit at the center of a swirling spiral of wind.
2. a spirit standing triumphantly at the very top of a mountain peak.
3. a spirit sitting at the bottom of a deep dark pit, a small light far above.
4. a spirit holding up a painted mask in front of its own face.
5. a wide-eyed spirit lying in bed under a starry night sky, unable to sleep.
6. a spirit surrounded by floating gears and technical symbols, one confused onlooker.
7. two small spirits holding hands, matching glowing hearts.
8. a spirit made of jagged black volcanic rock with glowing lava cracks.
9. a small muscular spirit flexing its abdominal muscles proudly.
10. a spirit holding up a tiny glowing billboard sign.
11. a spirit holding up a single glowing numeral one.
12. a spirit wearing a straw hat, holding a sprouting wheat stalk.
```

**Reference key** (not part of the prompt):
1. VORTEX (noun)
2. ZENITH (noun)
3. NADIR (noun)
4. FACADE (noun)
5. INSOMNIA (noun)
6. JARGON (noun)
7. KINSHIP (noun)
8. AA (noun)
9. AB (noun)
10. AD (noun)
11. AE (adjective)
12. AG (noun)

## Batch 14 of 20 — AH, AI, AL, AM, AR, AS, AX, AY, BA, BI, BO, BY

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit with mouth open in a delighted, surprised expression, sparkles around it.
2. a sleepy three-toed sloth creature spirit hanging from a branch.
3. a spirit grown from a red-dye tree, dripping crimson sap.
4. a spirit forming from a puff of glowing smoke, mid-existence.
5. a spirit shaped like a glowing letter R.
6. a spirit holding up a balance scale with two equal weights.
7. a lumberjack spirit mid-swing with a small axe, wood chips flying.
8. a spirit holding a ballot marked with a checkmark, cheering.
9. a spirit shaped like an Egyptian ba-bird with a small human face.
10. a spirit glowing in two blended colors side by side.
11. a spirit giving a friendly wave and thumbs up.
12. a spirit relaxing on a bench while others race past in a blur.
```

**Reference key** (not part of the prompt):
1. AH (verb)
2. AI (noun)
3. AL (noun)
4. AM (verb)
5. AR (noun)
6. AS (adverb)
7. AX (verb)
8. AY (noun)
9. BA (noun)
10. BI (noun)
11. BO (noun)
12. BY (noun)

## Batch 15 of 20 — DA, DO, ED, EF, EL, EM, EN, ES, ET, EX, FA, GI

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a warm fatherly spirit holding a smaller spirit's hand.
2. a determined spirit rolling up its sleeves, ready for action.
3. a spirit holding a book and wearing a tiny graduation cap.
4. a spirit shaped like a glowing letter F.
5. a spirit riding happily on a tiny elevated train car.
6. a spirit shaped like a glowing letter M holding a tiny ruler.
7. a spirit shaped like a glowing letter N, a little smaller than its cousin EM.
8. a spirit shaped like a glowing letter S.
9. an old-fashioned spirit happily munching on an apple.
10. a spirit dragging a big red X mark across a page.
11. a singing spirit with a musical note floating from its mouth.
12. a small spirit dressed in a white martial-arts uniform with a belt.
```

**Reference key** (not part of the prompt):
1. DA (noun)
2. DO (verb)
3. ED (noun)
4. EF (noun)
5. EL (noun)
6. EM (noun)
7. EN (noun)
8. ES (noun)
9. ET (verb)
10. EX (verb)
11. FA (noun)
12. GI (noun)

## Batch 16 of 20 — GO, HA, ID, IF, JO, KI, LA, LI, MA, ME, MI, MO

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit mid-run, dashing forward energetically.
2. a laughing spirit doubled over with joy.
3. a shadowy, instinct-driven spirit with wild untamed eyes.
4. a spirit standing before two glowing branching paths.
5. a spirit holding a small heart, blushing sweetly.
6. a spirit glowing with swirling inner energy in a martial-arts stance.
7. a singing spirit mid-song with a musical note beside it.
8. a spirit walking a very long winding road, measuring the distance.
9. a warm motherly spirit cradling a smaller spirit.
10. a spirit looking thoughtfully at its own reflection in a small mirror.
11. a singing spirit with a cheerful musical note.
12. a spirit glancing at a pocket watch with a 'just a moment' gesture.
```

**Reference key** (not part of the prompt):
1. GO (verb)
2. HA (noun)
3. ID (noun)
4. IF (noun)
5. JO (noun)
6. KI (noun)
7. LA (noun)
8. LI (noun)
9. MA (noun)
10. ME (noun)
11. MI (noun)
12. MO (noun)

## Batch 17 of 20 — MU, NE, NO, NU, OD, OE, OH, OK, OM, ON, OP, OR

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit shaped like the glowing Greek letter mu.
2. a spirit proudly holding up a family crest nameplate.
3. a spirit crossing its arms in an X, shaking its head.
4. a spirit shaped like the glowing Greek letter nu.
5. a spirit radiating a mysterious invisible aura of energy.
6. a small whirlwind spirit swirling over icy northern waters.
7. a spirit with wide eyes and an open mouth in sudden realization.
8. a spirit giving a cheerful thumbs-up.
9. a meditating spirit glowing with a soft sound-wave aura.
10. a spirit standing ready in a cricket batting stance.
11. a spirit made of swirling black-and-white optical-illusion patterns.
12. a spirit shimmering in heraldic gold, shield-shaped.
```

**Reference key** (not part of the prompt):
1. MU (noun)
2. NE (adjective)
3. NO (noun)
4. NU (noun)
5. OD (noun)
6. OE (noun)
7. OH (verb)
8. OK (adjective)
9. OM (noun)
10. ON (noun)
11. OP (noun)
12. OR (noun)

## Batch 18 of 20 — OS, OX, PA, PE, PI, PO, RE, SI, SO, TA, TE, TI

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a small spirit made of a single glowing bone shape.
2. a strong ox creature spirit pulling a small cart.
3. a warm fatherly spirit ruffling a smaller spirit's hair.
4. a spirit shaped like a glowing Hebrew letter pe.
5. a spirit shaped like the glowing Greek letter pi with a circle motif.
6. a small round spirit shaped like a chamber pot, sitting sheepishly.
7. a singing spirit with a musical note, mid-scale.
8. a singing spirit with a musical note.
9. a singing spirit with a musical note, mid-melody.
10. a spirit bowing gratefully amid sparkling thank-you hearts.
11. a singing spirit with a musical note.
12. a singing spirit reaching a high musical note.
```

**Reference key** (not part of the prompt):
1. OS (noun)
2. OX (noun)
3. PA (noun)
4. PE (noun)
5. PI (noun)
6. PO (noun)
7. RE (noun)
8. SI (noun)
9. SO (noun)
10. TA (noun)
11. TE (noun)
12. TI (noun)

## Batch 19 of 20 — UM, UP, UT, WO, YA, CWM, GNU, JEU, KOI, LEI, NIB, ORB

**Paste to Gemini:**
```
Create one image: a grid of 12 square panels, arranged in 4 columns × 3 rows, filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit scratching its head with a hesitant thought bubble of dots.
2. a spirit lifting a glowing arrow that points upward.
3. an old-fashioned singing spirit with an antique musical note.
4. a sorrowful, archaic spirit with a single weary teardrop.
5. a spirit happily biting into a juicy round Asian pear.
6. a spirit nestled in a glacier-carved mountain bowl.
7. a gnu wildebeest creature spirit.
8. a playful spirit juggling glowing wordplay symbols.
9. a koi fish creature spirit swimming in a slow circle.
10. a spirit wearing a colorful flower garland necklace.
11. a spirit shaped like a fountain pen nib, dripping a bead of ink.
12. a spirit made of a glowing crystal sphere.
```

**Reference key** (not part of the prompt):
1. UM (verb)
2. UP (verb)
3. UT (noun)
4. WO (noun)
5. YA (noun)
6. CWM (noun)
7. GNU (noun)
8. JEU (noun)
9. KOI (noun)
10. LEI (noun)
11. NIB (noun)
12. ORB (noun)

## Batch 20 of 20 — PYX, QAT, TSK, URN, VOX, WOK, YEP, ZEK, AVO

**Paste to Gemini:**
```
Create one image: a grid of 9 square panels, arranged in 4 columns, 2 full rows plus a final row of just 1 panel (left-aligned), filled in reading order (left-to-right, then top-to-bottom, panel 1 in the top-left corner). Cute chibi fantasy-spirit style — soft cel-shaded digital painting, big expressive eyes, simple rounded blobby body, glowing soft outline, transparent/checkered background per panel, centered. No text, letters, numbers, or labels anywhere in the image. Give each spirit its own distinct, memorable color suited to its concept — vary the colors across the grid rather than repeating the same palette. The panels, in reading order:

1. a spirit shaped like a small ornate golden box.
2. a spirit made of leafy green shrub branches.
3. a disapproving spirit wagging a finger, tongue mid-click.
4. a spirit shaped like an ornate footed urn vase.
5. a spirit made of a glowing megaphone with a voice waveform.
6. a spirit shaped like a sizzling wok pan with veggies flying.
7. a spirit giving an enthusiastic nod and thumbs up.
8. a weary, thin spirit wrapped in a tattered gray coat, breath frosting the air.
9. a spirit holding up a small shiny coin.
```

**Reference key** (not part of the prompt):
1. PYX (noun)
2. QAT (noun)
3. TSK (verb)
4. URN (noun)
5. VOX (noun)
6. WOK (noun)
7. YEP (adverb)
8. ZEK (noun)
9. AVO (noun)

