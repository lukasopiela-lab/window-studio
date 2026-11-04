# DRUTEX research (4 Nov 2026)

## Integration options
- No public DRUTEX API or product data feed was found.
- Dealers have a login-only **e-Portal**: https://e-portal.drutex.pl, plus a partner section: https://www.drutex.eu/en/dealers-auth/cooperation/
  → Ask the user's DRUTEX sales rep whether the e-Portal can export product data or price lists. If yes, build an importer.
- Otherwise: editable product database in Supabase, admin can add/edit/import products. Keep a `source_url` per product pointing to the official page.
- DRUTEX already runs its own door visualizer: https://wizualizator.drutex.pl/ – ours must differ by working on the customer's own house photo.
- Slovak product pages exist under https://www.drutex.eu/sk/vyrobky/<slug>.html
- DRUTEX photos, texts and brochures are copyrighted. Use them only with written permission from DRUTEX (the user should ask their rep). Linking to official pages and PDFs is fine.

## Product range (from the drutex.eu menu)
**PVC windows:** IGLO EXPERT (new), IGLO EDGE, IGLO ENERGY, IGLO ENERGY CLASSIC, IGLO ENERGY ALUCOVER, IGLO 5, IGLO 5 CLASSIC, IGLO LIGHT, IGLO EXT, IGLO PREMIER, IDEAL line (IDEAL NEO AD, NEO MD, NEO MD-FS, NEO MD MONOBLOCK, NEO MD RENOVATION, IDEAL 7000 NL)
**Aluminium windows:** MB-86N SI, MB-79N SI, MB-70HI, MB-70, MB-45
**Wooden windows:** SOFTLINE 68 / 78 / 88
**Wood-aluminium windows:** DUOLINE 68 / 78 / 88
**PVC doors:** IGLO ENERGY, IGLO 5, IGLO EDGE
**Aluminium doors:** D-ART Line, MB-86N SI, MB-79N SI+, MB-70HI, MB-70, MB-45, MB-78EI (fire doors), PIVOT
**Wooden doors:** SOFTLINE 68 / 78 / 88
**Lift & slide HS:** IGLO-HS, IGLO-HS ALUCOVER, MB-77HS HI, MB-77HS HI MONORAIL, MB-59HS HI, SOFTLINE HS, DUOLINE HS
**Slide:** IGLO EDGE SLIDE, IGLO SLIDE, MB-SLIDE, COR VISION, COR VISION PLUS
**Folding doors:** MB-86 FOLD LINE HD, SOFTLINE 68
**Tilt & slide PSK:** IGLO EXPERT PSK, IGLO ENERGY PSK, IGLO ENERGY CLASSIC PSK, IGLO 5 PSK, IGLO 5 CLASSIC PSK, IGLO LIGHT PSK, MB-70 / MB-70HI PSK, SOFTLINE PSK, DUOLINE PSK
**Shutters:** aluminium shutters (adaptive), RDZ shutters, PVC shutters (top-mounted), roller shutters with styrofoam box
**Other:** exterior venetian blinds, pleated insect screens, garage doors (D-GATE), facades MB-SR50N, winter gardens MB-WG60, pergolas, smart home, accessories ("Extras")

## Verified specs (only these – everything else must be entered from official sources)
Source: https://www.drutex.eu/en/products/iglo-slide.html (product page + its comparison table)

| Product | Chambers | Installation depth | Glass packages |
|---|---|---|---|
| IGLO SLIDE | 3 | 82 mm | 24 mm, Ug = 1.1 W/(m²K) as standard (range 20–36 mm), class A profile |
| IGLO LIGHT PSK | 5 | 70 mm | 24–40 mm |
| IGLO ENERGY PSK | 7 | 70 mm (as stated in the table) | 24–48 mm |
| IGLO EDGE SLIDE | 6 | 163 mm | 48 mm, 54 mm |
| IGLO 5 PSK | 5 | 70 mm | 24–40 mm |
| DUOLINE PSK | solid profile | 82/92 mm | DL68: 24–44 mm, DL78: 24–50 mm |

IGLO SLIDE standard equipment: Siegenia fittings with height-adjustable carts, 3 types of aluminium handles, 24 mm 2-pane argon-filled glazing Ug = 1.1, galvanised steel spacer, V-perfect weld, brush sealing, black gaskets, 2 mm steel reinforcement in frame and sash.
PVC terrace systems: over 30 veneer colours (full list with codes on the IGLO SLIDE page). Spacer: galvanised steel standard, Swisspacer Ultimate optional.

Slovak leaflets (drutex.pl/media/_upload/_promotion/ulotki/sk/):
- Iglo Energy: 7-chamber class A profiles, 82 mm installation depth, triple sealing system.
- Iglo Light: narrow frame and sash profiles; available in 43 Renolit foil shades, white or brown core.
