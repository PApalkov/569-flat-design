# Flat 569: prompts for photorealistic renders (ChatGPT)

The prompts are in English: image models follow them more precisely than Russian.
Each prompt describes **the current design**, matching `index.html` (v1) and `v2/index.html`.

## How to get good results

1. **Always attach a layout reference.** Open the site, take a screenshot from roughly the same viewpoint
   (3D tab → «Пройтись», tap the floor where you want to stand, then turn). Attach it and keep the line
   *"Use the attached 3D screenshot as the exact layout reference"*. Without it, ChatGPT invents its own room.
2. **Attach material photos** from `materials/`:
   - laminate: `photo_2026-10-30_17-06-58.png`, `photo_2026-10-30_17-26-38.png`
   - bathroom wood-look tile: `photo_2026-10-31_06-27-03.png`
   - laminate and tile side by side: `photo_2026-10-31_06-57-34.jpg`
3. Paste the **shared style block** first, then the room prompt, all in one message.
4. One image per message. Fix things with short follow-ups ("keep everything, make the floor planks
   longer and narrower", "remove the extra chair", "the window is on the short wall, not the long one").
5. If it drifts after a few edits, start a new chat with the same prompt plus the reference.

---

## Shared style block (paste before every room prompt)

```
Photorealistic interior photograph of a real, finished apartment in a new building in Russia, not a CGI showroom.
Shot on a full-frame camera with a 20–24 mm lens at 1.5 m height, vertical lines kept straight (no keystoning), natural daylight from the window, soft realistic shadows, slight lived-in imperfection.
Ceiling height 2.70 m, smooth white matte ceiling with flat round surface-mounted LED ceiling lights (no spotlights, no stretch-ceiling gloss).
Walls: smooth painted plaster, warm light grey (#C9C4BC), white skirting.
Floor in all rooms except the bathroom and the entrance pocket: laminate, light warm-brown natural oak look (average colour about #B39A85), straight planks 1380 × 193 mm, random staggered joints, subtle grain with occasional small knots, matte, fine micro-bevel. NOT herringbone, NOT chevron, NOT dark or orange wood.
Hardware, taps and lamp details: matte black.
Keep proportions exactly as described; do not add furniture, rugs or decor that is not listed. Room sizes are small and real — do not make the space look bigger than it is.
```

---

## 1. Kitchen-living room, v1 (L-shaped kitchen + bar), view from the window towards the kitchen

```
Room: one long room 6.90 × 2.81 m. The camera stands near the window (window behind the camera, on the short west wall) and looks along the room to the kitchen at the far short wall.
Right long wall (shared with the neighbours): a sofa 200 × 90 cm, light grey-beige fabric (#B5B2AB), two graphite cushions, an oak-coloured knitted throw; above it an abstract painting 100 × 70 in beige-brown-graphite with a thin black frame; a black floor lamp with a linen shade in the corner by the window; a tall potted plant by the window.
Left long wall (shared with the bedroom): a 55" TV mounted on the wall above a low light grey TV unit 160 × 38 cm.
In front of the sofa: a light textured rug 220 × 145 cm.
Far end — the kitchen, L-shaped:
- End wall 2.21 m, left to right: freestanding black-graphite fridge 60 cm with a graphite cabinet above it, dishwasher 45 (integrated, grey gloss front), sink unit 60 with a black quartz sink and black tap, corner drawer unit 56.
- Along the right (neighbours') wall from the corner: base 45, 60 cm four-burner hob with oven below, base 60; above them a microwave built into the bottom of a 60 cm wall unit.
- Base fronts: grey gloss (#767B81), handleless with black rail handles on drawers. Wall units in two rows up to the ceiling: grey gloss lower row, graphite matte (#3C4046) top row of mezzanine cabinets. One open matte-black niche over the dishwasher with dishes.
- Worktop 38 mm, backsplash panel and plinth: warm "Wotan oak" wood decor (#A9803F worktop, darker oak plinth).
- A bar counter 160 × 60 cm, height 90, Wotan oak, sticking out perpendicular from the right wall right after the last base unit; two half-bar stools in cream bouclé (seat 65 cm) at its free end, facing each other; above the bar two pendant lamps with cream pleated cylindrical shades and black caps.
- An internal partition 1.30 m with a doorway gap to the hall is on the left side near the kitchen.
Curtains: floor-length natural linen, beige, on a black rod at the window behind the camera (visible at the frame edge).
Time: late afternoon, warm sun from the west window behind the camera, long soft light on the floor.
Use the attached 3D screenshot as the exact layout reference and the attached laminate photos for the floor.
```

## 2. Kitchen-living room, v1, view from the kitchen towards the window

```
Camera stands by the bar counter in the kitchen area and looks towards the window on the far short wall.
The window is 1.70 m wide, sill height 0.80, top 2.45, placed against the right corner (right long wall = bedroom wall); 1.10 m of plain wall between the window and the left corner.
Floor-length beige linen curtains on both sides of the window, a tall potted plant beside it.
Left long wall (neighbours): sofa 200 × 90, light grey-beige, graphite cushions, oak-coloured throw, abstract painting 100 × 70 above, black floor lamp in the corner by the window.
Right long wall (bedroom): 55" TV over a light grey TV unit 160 × 38.
Foreground: the end of the Wotan oak bar counter with one cream bouclé half-bar stool, one cream pleated pendant lamp visible at the top of the frame.
Laminate floor as in the style block, planks running along the room towards the window.
Morning, soft diffuse daylight from the window (west-facing, no direct sun).
Use the attached 3D screenshot as the exact layout reference.
```

## 3. Kitchen v2 (single-wall kitchen + dining table)

```
Same long room 6.90 × 2.81 m, camera in the living area looking towards the kitchen on the short end wall.
The whole kitchen is on the 2.21 m end wall, left to right: sink unit 60 in the corner (black quartz sink, black tap), work unit 41, unit 60 with a 2-burner domino hob (30 cm wide, burners one behind the other), freestanding black-graphite fridge 60 at the right end.
Wall units: dish-drainer unit 41 over the work unit, unit 60 with a built-in microwave in its bottom, a 60 cm hood unit over the hob; a graphite mezzanine row up to the ceiling.
Fronts grey gloss (#767B81) below and in the lower wall row, graphite matte (#3C4046) on top and on the fridge housing. Worktop, backsplash panel and plinth in warm Wotan oak.
No bar counter. Instead, in the middle of the kitchen half of the room: a freestanding rectangular dining table 120 × 80, height 75, with four cream bouclé dining chairs, two pendant lamps with cream pleated shades over the table.
Sofa (light grey-beige, graphite cushions) on the right long wall in the foreground, TV on the left wall.
Laminate floor as in the style block. Daylight from the window behind the camera.
Use the attached 3D screenshot as the exact layout reference.
```

## 4. Bedroom

```
Bedroom 4.58 × 2.70 m, narrow and long. Window 1.60 m on the short west wall, placed against the right (north) corner, beige linen floor-length curtains.
Bed 160 × 200 with an upholstered headboard in warm grey fabric (#9B9790), headboard against the right long wall (north, shared with neighbours); simple light bedding with a slightly darker folded throw at the foot. Two small black wall sconces on either side of the headboard. No bedside tables.
Opposite short wall (east): a sliding-door wardrobe 178 × 60, height 2.50, flat matte grey fronts (#7A7F85), from the north wall to the door.
Bedroom door 60 cm in the east wall near the left corner.
Walls warm light grey, laminate floor as in the style block, planks running along the room towards the window.
Camera stands by the door looking towards the window, morning light.
Calm, uncluttered, nothing else in the room.
Use the attached 3D screenshot as the exact layout reference.
```

## 5. Bathroom, view from the door (toilet corner and wood-look wall)

```
Small bathroom 2.19–2.33 × 1.53 m (3.5 m²), ceiling 2.70, one flat round moisture-proof ceiling light. The camera stands in the open doorway on the south wall, slightly wide (20 mm), looking in.
Floor: large wood-look porcelain planks 20 × 120 cm in light warm-brown oak (same tone as the laminate in the rest of the flat, about #B8A08C), visible grain and small knots, thin grout lines, planks laid along the long side of the room.
Right wall (east): fully clad in the SAME wood-look porcelain planks, laid VERTICALLY floor to ceiling, so the floor visually turns up the wall. In front of it a white floor-standing close-coupled toilet, back to this wall, facing left; above the cistern a matte black electric ladder towel rail 50 × 72.
Back wall (north): a fluted vertical wood panel in dark oak; against it, left to right: a 60 cm vanity with two drawers in matte grey (#7A7F85) and an inset white basin with a tall matte black tap, a white front-loading washing machine 60 cm, a narrow 22 cm closed panel up to the wall; ONE continuous light stone countertop (about 144 cm) over all three. A 60 × 80 backlit mirror with a thin black frame above the basin.
Left wall (west): a white acrylic bathtub 150 × 70 along the whole wall, an 80 cm fixed clear glass screen with a thin black profile at the tap end, a matte black wall-mounted bath mixer with a shower rail.
All other walls: large-format porcelain tiles imitating light warm travertine (#E6E0D6), matte.
Realistic and tight — do not enlarge the room.
Use the attached 3D screenshot as the exact layout reference and the attached tile photo for the floor and the toilet wall.
```

## 6. Bathroom, vanity and washer wall close-up

```
Close view of the north wall of a small bathroom, camera at 1.4 m, 28 mm lens, slightly from the right.
Fluted vertical dark-oak panel covering the wall from the bathtub to the right corner.
In front of it: matte grey two-drawer vanity 60 cm with an inset white basin and a tall matte black tap; to its right a white front-loading washing machine under the same countertop; then a 22 cm closed panel to the corner. One continuous light stone countertop, 92 cm high.
Above the basin a 60 × 80 mirror with a thin black frame and soft LED backlight.
Right corner: the wall with vertical wood-look porcelain planks and the edge of a white toilet cistern with a black towel rail above it.
Floor: wood-look porcelain planks 20 × 120 in light warm-brown oak.
A rolled towel and one soap dispenser on the countertop, nothing else.
```

## 7. Hallway

```
Small hallway about 3.1 m², camera at the front door looking into the flat.
Left: a full-height wardrobe 118 × 50 to the ceiling, flat matte grey fronts (#7A7F85), handleless.
On the right, on the bathroom wall: a tall mirror 66 × 170 with a thin black frame and a small bench with a light upholstered seat and dark wood legs below it.
Doorways: to the bathroom (70 cm, white flush door) on the right, to the bedroom (60 cm) straight ahead, and an open 0.92 m passage into the living room on the left where you can see the laminate floor continuing and part of the kitchen.
Floor: the same light warm-brown oak laminate, planks running towards the living room; in the small entrance pocket by the front door, 60 × 60 porcelain tiles in warm grey-beige, joined to the laminate with a straight line along the wall.
A linear ceiling light along the hallway, warm white. Walls warm light grey.
Use the attached 3D screenshot as the exact layout reference.
```

---

## Useful follow-up fixes

- `Keep everything exactly the same, only change the floor to straight laminate planks 1380 × 193, light warm-brown oak, no herringbone.`
- `The room is too big. It is only 2.81 m wide — bring the walls closer, keep the furniture sizes.`
- `Remove everything that is not in my list.`
- `Same image, evening: ceiling lights off, pendant lamps and under-cabinet LED strip on, warm 2700K.`
- `Same image, but swap wall colour to warm sand (#D6CCBD)` (the other colour schemes are in the «Гаммы» tab).
