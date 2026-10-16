# ASSETS — provenance and licensing

All art in `public/assets/` is **CC0 (public domain)**. No CC-BY assets were used, so
**no attribution is legally required**; every author is credited below anyway. No ripped
or copyrighted commercial game assets (C&C, Red Alert, StarCraft, WarCraft, DoW, …) were
used anywhere.

Raw source archives are kept in `vendor/assets/` (git-ignored later) as provenance.
`vendor/scratch/` holds the (reproducible) extraction + normalisation scripts
(`build.mjs`, `verify.mjs`, `seamtest.mjs`, `ascii.mjs`, …).

Everything in `public/assets/` was produced by `node vendor/scratch/build.mjs`.

---

## Provenance table — `public/assets/`

License column: all **CC0 1.0** (`http://creativecommons.org/publicdomain/zero/1.0/`).

### terrain/

| file | pack | author | license | source URL |
|---|---|---|---|---|
| `terrain/terrain_tileset.png` | Tower Defense (Top-Down) — `towerDefense_tile124/060/198/267` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/tower-defense-top-down |
| `terrain/terrain_tileset.png` (tiles `asphalt`, `road_h`, `road_v`, `road_cross`) | Racing Pack — `Tiles/Asphalt road/road_asphalt22/20/01/57.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/racing-pack |
| `terrain/terrain_tileset.png` (tile `rock`, composited) | Tower Defense (Top-Down) `towerDefense_tile060.png` + Racing Pack `Objects/rock1.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/tower-defense-top-down , https://kenney.nl/assets/racing-pack |
| `terrain/tileset.json` | generated manifest | — | — | — |

### units/

| file | pack | author | license | source URL |
|---|---|---|---|---|
| `units/tank.png` | Top-Down Tanks — `PNG/Tanks/tankGreen.png` | Kenney Vleugels (kenney.nl) | CC0 | https://opengameart.org/content/top-down-tanks-redux (mirror of Kenney "Top-Down Tanks"; archive `vendor/assets/Kenney_topdownTanks.zip`) |
| `units/apc.png` | Pixel Vehicle Pack — `PNG/Cars/suv_military.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/pixel-vehicle-pack |
| `units/truck.png` | Pixel Vehicle Pack — `PNG/Cars/truck.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/pixel-vehicle-pack |
| `units/harvester.png` | Pixel Vehicle Pack — `PNG/Cars/tractor.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/pixel-vehicle-pack |
| `units/car.png` | Pixel Vehicle Pack — `PNG/Cars/sedan.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/pixel-vehicle-pack |
| `units/soldier.png` | Top-Down Shooter — `PNG/Soldier 1/soldier1_machine.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/top-down-shooter |
| `units/units.json` | generated manifest | — | — | — |

### buildings/

| file | pack | author | license | source URL |
|---|---|---|---|---|
| `buildings/hq.png` | RTS Pack: Sci-Fi — `PNG/Default size/Structure/scifiStructure_05.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/barracks.png` | RTS Pack: Sci-Fi — `scifiStructure_02.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/factory.png` | RTS Pack: Sci-Fi — `scifiStructure_03.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/power.png` | RTS Pack: Sci-Fi — `scifiStructure_08.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/refinery.png` | RTS Pack: Sci-Fi — `scifiStructure_16.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/storage.png` | RTS Pack: Sci-Fi — `scifiStructure_11.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/turret.png` | Tower Defense (Top-Down) — `towerDefense_tile204.png` (twin-barrel gun turret) | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/tower-defense-top-down |
| `buildings/wall.png` | RTS Pack: Sci-Fi — `scifiStructure_01.png` (full-tile-width wall segment) | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-rts |
| `buildings/buildings.json` | generated manifest | — | — | — |

### fx/

| file | pack | author | license | source URL |
|---|---|---|---|---|
| `fx/explosion.png` | Tanks (pack) — `tank_explosion5/6/7/8.png` (growing fireball) | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/tanks |
| `fx/explosion_small.png` | Tanks (pack) — `tank_explosion10/11/12.png` (small puff) | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/tanks |
| `fx/smoke.png` | Top-Down Tanks — `PNG/Smoke/smokeGrey0..5.png` | Kenney Vleugels (kenney.nl) | CC0 | https://opengameart.org/content/top-down-tanks-redux (mirror; archive `vendor/assets/Kenney_topdownTanks.zip`) |
| `fx/muzzle_flash.png` | Muzzle Flash particle sheet — `muzzleFlash0.png` (4 cells) | **leftshoe18** (OpenGameArt) | CC0 | https://opengameart.org/content/muzzle-flash-particle-sheet |
| `fx/fx.json` | generated manifest | — | — | — |

### ui/

| file | pack | author | license | source URL |
|---|---|---|---|---|
| `ui/cursor_default.png` | Cursor Pack — `PNG/Basic/Default/pointer_c.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/cursor-pack |
| `ui/cursor_attack.png` | Cursor Pack — `PNG/Basic/Default/target_round_a.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/cursor-pack |
| `ui/cursor_move.png` | Cursor Pack — `PNG/Basic/Default/navigation_n.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/cursor-pack |
| `ui/cursor_nohold.png` | Cursor Pack — `PNG/Basic/Default/cursor_disabled.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/cursor-pack |
| `ui/icon_credits.png` | Tower Defense (Top-Down) — `towerDefense_tile296.png` (yellow gem used as the credits/currency icon) | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/tower-defense-top-down |
| `ui/icon_power.png` | Game Icons — `PNG/White/2x/power.png` | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/game-icons |

### sfx/

| file | role | pack | author | license | source URL | original file |
|---|---|---|---|---|---|---|
| `sfx/explosion.ogg` | big explosion | Kenney Sci-Fi Sounds | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-sounds | `explosionCrunch_004.ogg` |
| `sfx/explosion_small.ogg` | small explosion / impact | Kenney Sci-Fi Sounds | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/sci-fi-sounds | `explosionCrunch_000.ogg` |
| `sfx/cannon.ogg` | tank cannon / heavy gun | 25 CC0 bang / firework SFX | **rubberduck** | CC0 | https://opengameart.org/content/25-cc0-bang-firework-sfx | `cannon_02.ogg` |
| `sfx/rifle.ogg` | rifle burst | 25 CC0 bang / firework SFX | **rubberduck** | CC0 | https://opengameart.org/content/25-cc0-bang-firework-sfx | `shot_01.ogg` |
| `sfx/build_complete.ogg` | construction complete chime | Kenney Music Jingles | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/music-jingles | `8-Bit jingles/jingles_NES13.ogg` |
| `sfx/unit_ready.ogg` | unit-ready chime | Kenney Interface Sounds | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/interface-sounds | `confirmation_002.ogg` |
| `sfx/error.ogg` | error / buzz | Kenney Interface Sounds | Kenney Vleugels (kenney.nl) | CC0 | https://kenney.nl/assets/interface-sounds | `error_005.ogg` |

### music/

| file | duration | pack | author | license | source URL | original file |
|---|---|---|---|---|---|---|
| `music/theme_industrial.ogg` | 85.1 s | Abandoned Steel Mill | **Spring Spring** | CC0 | https://opengameart.org/content/abandoned-steel-mill | `Abandoned Steel Mill_0.ogg` |
| `music/theme_covert_ops.mp3` | 99.9 s | Covert Operations | **artisticdude** | CC0 | https://opengameart.org/content/covert-operations | `covert_operations.mp3` |
| `music/theme_metal_city.ogg` | 178.2 s | Escape from Metal City | **congusbongus** | CC0 | https://opengameart.org/content/escape-from-metal-city | `escape_from_metal_city_0.ogg` |

Every track is within the required 30 s–3 min range and has a militaristic / electronic
RTS feel. Durations were measured from the Ogg granule position / MP3 frame headers
(`vendor/scratch/audiodur.mjs`; cross-checked to 0 ms against `ffprobe`), not taken from
the source pages. The CC0 license of all four OpenGameArt items above was re-checked
directly on its OpenGameArt page during this session (`vendor/scratch/oga_probe2.ps1`).

⚠️ **Loop point:** `theme_industrial.ogg` and `theme_metal_city.ogg` have energy-matched
start/end and no leading or trailing silence, so they loop cleanly. `theme_covert_ops.mp3`
has **1.011 s of trailing silence**, so it loops with a ~1 s gap — trim the tail if you
need a seamless loop. (The audio was never auditioned, so the loop points are measured,
not heard.)

A machine-readable copy of all of the above (including per-file `role`, `originalName` and
`durationSec`) is written to `public/assets/audio_sources.json`.

Sources that were deliberately **rejected** during audio sourcing, for the record:
qubodup "Sci-Fi RTS War Unit Sounds" (CC0) — `artil.action.wav` is a spoken voice line,
not cannon fire; Tabasco "Gunshot Sounds" — tagged CC0 on OpenGameArt but its bundled
`creativecommons.txt` says CC-BY 3.0 (Vincent Sevedge), i.e. a licence conflict; and
`gunfire_sfx.wav` (CC0) — only 0.21 s of audio inside a 2.00 s file.

---

## Normalisation notes (how the files were produced)

- **Terrain** — `terrain_tileset.png` is a single 192×192 sheet, **3 columns × 3 rows of
  64 px tiles, no padding** (exactly the layout in `tileset.json`).
  - `grass` (0), `dirt` (1), `sand` (2), `water` (4) are 64 px tiles from Kenney's
    *Tower Defense (Top-Down)* tilesheet, chosen programmatically as the **most textured
    tiles whose 1 px border is a single flat colour**, so they tile with themselves with
    **zero** seam discontinuity (verified — see `vendor/scratch/seamtest.mjs`).
  - `asphalt` (3) is Kenney *Racing Pack* `road_asphalt22.png`, downscaled 128 → 64 px; it
    is a flat, fully seamless asphalt surface.
  - `road_h` (6) = `road_asphalt20.png`, `road_v` (7) = `road_asphalt01.png`,
    `road_cross` (8) = `road_asphalt57.png`, all downscaled 128 → 64 px. Verified: `road_h`
    tiles horizontally, `road_v` tiles vertically, `road_cross` tiles on both axes — the
    same behaviour as the untouched source tiles. As in the source pack, the *cross
    section* of a road is deliberately asymmetric (top-down 3/4-view kerb), so a road strip
    is not meant to stack against itself on its short axis.
  - `rock` (5) is **composited**: Kenney *Tower Defense* dirt tile (`towerDefense_tile060`)
    as the ground with Kenney *Racing Pack* `Objects/rock1.png` scaled to 48×39 and centred
    on top. No pixels were drawn from scratch — two CC0 Kenney sprites were combined. The
    composite was verified seamless (border delta 0 on all four edges).
- **Units** — every `units/<name>.png` is a **horizontal strip of 8 frames**
  (`frameWidth × 8` wide, `frameHeight` tall), direction 0 = source orientation, going
  clockwise in 45° steps.
  - ⚠️ **The 8 facings are generated, not hand-drawn.** None of the source packs ship 8
    pre-drawn facings for these units (they ship a single top-down frame that the game is
    expected to rotate). Each source frame was upsampled 4×, rotated 45°·n with a
    transparent background, downsampled back, and centred on a square frame — so the scale
    is identical in all 8 directions and a top-down sprite stays geometrically correct.
    `directions: 8` and `framesPerDirection: 1` in `units.json` describe exactly this.
  - ⚠️ **Style mix.** Vehicles come from two different Kenney packs: `tank` is smooth
    vector art (*Top-Down Tanks*), while `apc`, `truck`, `harvester` and `car` are
    low-resolution 4-bit pixel art (*Pixel Vehicle Pack*, nearest-neighbour scaled so the
    pixels stay crisp). `soldier` is smooth vector art (*Top-Down Shooter*). They are all
    genuinely top-down and each file is exactly the vehicle its source filename says, but
    they are **not** a visually uniform set.
- **Buildings** — each is a single frame, transparent background, padded (centred) onto a
  uniform 64×64 canvas so all buildings share one anchor size; `buildings.json` records
  `width`/`height`/`anchor` for each.
  - ⚠️ **The building names are a semantic assignment, not pack metadata.** Kenney packs
    ship numbered files (`scifiStructure_01.png` … `scifiStructure_16.png`) with no
    semantic names, and the same applies to the *Tower Defense* tilesheet. The mapping was
    chosen by inspecting each sprite's shape and footprint (see the exact source file per
    building in the table above, so any mapping can be re-assigned trivially). `hq` is the
    largest/widest structure, `barracks` the windowed block, `factory` the structure with
    the machinery extension, `power` the twin-reactor block, `refinery`/`storage` the
    tank/container structures, `wall` the full-tile-width low segment, and `turret` is a
    genuine twin-barrel gun turret sprite from the *Tower Defense* pack (the *Sci-Fi RTS*
    pack has no unmistakable gun turret).
  - ⚠️ `turret` therefore comes from a different Kenney pack than the other buildings.
    Both are Kenney flat-vector art at 64 px and read as one set, but it is a mix.
- **FX** — every `fx/<name>.png` is a horizontal strip.
  - `explosion` (4 frames) and `explosion_small` (3 frames) are assembled from separate
    *Tanks* pack sprites that form a growth sequence (14→33→41→59 px and 14→33→41 px);
    each frame was centred on a common square frame at native scale, which is what
    preserves the animation. ⚠️ These were **not** authored as a single strip in the source
    pack — the grouping is our reading of the size progression.
  - `smoke` (6 frames) is *Top-Down Tanks* `smokeGrey0..5.png` — a genuine 6-frame
    sequence — each frame centred on a common 112×112 frame.
  - `muzzle_flash` (4 frames) is the 4 cells of *Muzzle Flash particle sheet*
    (`muzzleFlash0.png`, 512×128, RGB with a solid black background). The black background
    was **keyed to transparent** (alpha = luminance, black → alpha 0) and each cell was
    downscaled 128 → 64 px. These 4 cells are 4 muzzle-flash shapes from the sheet; they can
    be used as variants or played in order.
- **UI** — the four cursors are copied from Kenney's *Cursor Pack* and resized to 32×32
  with `fit: contain` (no cropping, no distortion). `icon_power.png` is Kenney *Game Icons*
  `power.png` scaled 100 → 64 px. `icon_credits.png` is the *Tower Defense* pack's yellow
  gem sprite — that pack has no coin, and a gem is used as the currency icon instead.
  ⚠️ The two icons come from two different packs and therefore do not share a style.

## Verification performed

- Every file in `public/assets/` was re-opened after the build: all PNGs decode, have
  non-zero size, and their pixel dimensions match the values in the JSON manifests
  (`units.json`, `buildings.json`, `fx.json`, `tileset.json`).
- Every audio file's magic bytes were checked against its extension (`OggS`, `RIFF/WAVE`,
  ID3/MPEG frame sync).
- Terrain tiling was measured numerically, not assumed: the wrap-around discontinuity of
  each tile was compared against the largest discontinuity *inside* the tile
  (`vendor/scratch/seamtest.mjs`, `seamdelta.mjs`).
- JSON manifests were re-read from disk and cross-checked against the actual PNG headers
  (`vendor/scratch/verify.mjs`).

## MISSING

**Nothing required by the brief is missing.** All eight categories are filled:
terrain (all 9 named tiles), units (tank / APC / truck / harvester / car / soldier),
buildings (hq / barracks / factory / power / refinery / storage / turret / wall),
fx (explosion / explosion_small / muzzle_flash / smoke), ui (4 cursors + 2 icons),
sfx (7 roles) and music (3 tracks). No placeholder, dummy or broken file was created.

The following are **quality caveats, not missing assets** (all detailed in
"Normalisation notes" above):

1. **No hand-authored 8-direction unit art.** The 8 facings in every `units/*.png` are
   generated by rotation of a single top-down frame. If real hand-drawn 8-direction RTS
   units are wanted, they must be sourced separately — the free CC0 packs checked here
   (Kenney *Top-Down Tanks*, *Pixel Vehicle Pack*, *Top-Down Shooter*, *Sci-Fi RTS*,
   *Racing Pack*, *Tanks*) all ship single facings only.
2. **Unit art style is not uniform** (`tank`/`soldier` are smooth vector, the other four
   vehicles are pixel art).
3. **`turret` comes from a different pack** than the other buildings.
4. **Building names are semantic guesses**, not source metadata.
5. **`icon_credits.png` is a gem, not a coin** — no coin exists in the packs used.
6. **The explosion / explosion_small / muzzle_flash frame groupings are our
   interpretation** of source sprites, not an authored animation.
7. **Road tiles do not stack on their short axis** (asymmetric kerb), by design of the
   source pack.

### Verified-reachable fallbacks (if a category ever needs replacing)

All of these were fetched successfully (HTTP 200) during this session:

- Terrain with water/rock: `https://opengameart.org/sites/default/files/terrain_tiles24.png`
  (Matiaan, CC0 — 256×256, grass/beach/water).
- Larger terrain sheets: `https://opengameart.org/sites/default/files/factory_tileset.png`
  (CC0, 832×512 industrial tileset),
  `https://opengameart.org/sites/default/files/03-tiles_1.png` ("Warped City", CC0).
- Alternative road/urban tiles: `https://opengameart.org/sites/default/files/Road_test.png`
  ("top down Road Tileset", CC0 — note: a rendered map, not a clean tile sheet).
- Alternative buildings: `https://opengameart.org/sites/default/files/colony-db32-buildings-ready.png`
  ("Colony sim assets", CC0 — 16 px packed atlas, no metadata),
  `https://opengameart.org/sites/default/files/tileset-export_0.png`
  ("Warped Top-Down Tech Lab 2", CC0).
- More muzzle-flash sprites: `https://opengameart.org/sites/default/files/muzzle_flashs.zip`
  ("16 Toon Muzzle flash", CC0) and
  `https://opengameart.org/sites/default/files/rc_art_-_muzzle_effects.zip`
  (CC0 muzzle effects, fire/ion/melee).
- Kenney catalogue (browse for more CC0 2D RTS art):
  https://kenney.nl/assets/series:RTS (verified list: `sci-fi-rts`, `medieval-rts`).
