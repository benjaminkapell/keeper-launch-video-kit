# Keeper brand sheet

Source of truth: the live site, [keeperlockers.com](https://www.keeperlockers.com). If this sheet and the site disagree, the site wins.

## Name

- Brand: **Keeper**. Write it like that in titles and supers.
- Company (legal lines only): Keeper Lockers UG (haftungsbeschränkt). Never "GmbH".
- Mascot: **Keevy**, the little suitcase.
- Claim: **Explore Your Freedom**
- Domain: keeperlockers.com

## Colour

![palette](brand/palette.png)

| Name | Hex | Use |
|---|---|---|
| Coral | `#FF6B4A` | Primary. Headline accents, buttons |
| Orange | `#FF8C42` | Middle of the gradient |
| Marigold | `#FFB347` | End of the gradient |
| Teal | `#4ECDC4` | The only cool accent. Small doses |
| Cream | `#FFF8F5` | Light backgrounds |
| Ink | `#1A1A1A` | Text, dark backgrounds |
| Muted | `#6B6B6B` | Secondary text |

**Signature gradient:** coral → orange → marigold at 135°
`linear-gradient(135deg, #FF6B4A 0%, #FF8C42 50%, #FFB347 100%)`

Keevy's own body runs warm orange at the top to teal-blue at the bottom. That is why teal belongs in the palette. The lockers in the illustrations carry the same top-to-bottom fade.

Machine-readable copy: `brand/colors.css`.

## Type

| Role | Font | Notes |
|---|---|---|
| Headlines, big numbers | **Bricolage Grotesque** | Bold / ExtraBold, tight tracking |
| Body, captions, UI | **DM Sans** | Regular / Medium / Bold |

Both are free (SIL Open Font License). Variable TTFs are in `brand/fonts/` — install them and pick the weight in your editor.

## Logo

The logo is **Keevy + the word "Keeper"** set in Bricolage Grotesque ExtraBold. Coral on light backgrounds, white over photos and the gradient, ink where coral doesn't work.

| File | Use |
|---|---|
| `brand/logo/png/keeper-lockup-3d-{coral,white,ink}.png` | The main logo: 3D Keevy + wordmark, transparent, ~3900px wide |
| `brand/logo/png/keeper-wordmark-{coral,white,ink}.png` | Wordmark alone, transparent |
| `brand/logo/svg/keeper-wordmark-{coral,white,ink}.svg` | Wordmark as true vector outlines — scales to any size, no font needed |
| `brand/logo/svg/keeper-lockup-{coral,white,ink}.svg` | Fully vector lockup with a flat Keevy icon |
| `brand/logo/svg/keevy-icon-flat.svg` | Flat vector Keevy for very small sizes |

The flat Keevy is a simplified stand-in drawn for this kit. Prefer the 3D Keevy wherever there is room.

Ready-made end cards (4K, vertical and horizontal, cream and gradient) are in `end-cards/`, with empty backgrounds in `end-cards/background-only/` for animating the pieces yourself.

## Keevy

- Soft, matte, rounded suitcase with a fixed loop handle, dot eyes, small smile, stubby arms and legs.
- Friendly and a bit cheeky. Annoyed only when hauling luggage or paying by the coin (`keevy-struggle`, `keevy-angry-coins`) — those two are the "before Keeper" poses.
- Don't stretch, recolour or add a mouth full of teeth to the happy poses. Don't put a telescoping trolley handle on Keevy.
- `brand/mascot-keevy/hi-res/*-transparent-4k.png` are the four hero poses (wave, celebrate, struggle, walk) at ~2700px on transparent backgrounds — use these full-frame.
- `brand/mascot-keevy/poses/` are 26 more transparent poses around 600px — fine as small on-screen elements.

## Look and feel

Warm, bright, optimistic. Golden-hour light, people moving freely with empty hands. Cream and coral, never cold corporate blue. Rounded corners everywhere. Motion is calm for navigation and playful only at the happy moments (locker opens, bag is stored, walking away free).

## Voice

Short, plain, confident. Says what it costs and how it works without hype.

- "Drop your bags. Explore freely."
- "Pay per minute, not per hour."
- "No keys. No coins. No queues."
- "Travel light."

German uses "du".
