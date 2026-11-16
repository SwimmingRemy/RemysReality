# Licence scope — SR_CL Remy's Reality

This file states which terms apply to which files in this distribution.
It enumerates them exactly. **No directory-wide inference applies to any
file not listed here.** If a file is not listed, it is not covered by any
grant in this distribution.

Author of the material listed in section 1: SwimmingRemy.
Terms are as at this build. See section 5.

---

## 1. Covered by AGPL-3.0-only, plus the additional permission

Licence: `GNU Affero General Public License, version 3 only`
Additional permission: `SRCL-BeamNG-Permission.txt` (AGPL section 7)
Full licence text: `LICENSE`

These files are the "RR Covered Material" referred to in
`SRCL-BeamNG-Permission.txt`. They are original work by SwimmingRemy,
**except for the three data files in section 1b**, whose underlying facts
come from public-domain sources and are not claimed by anyone here.

Root files:

```
info.json
README_RemysReality.txt
```

Code and data:

```
gameplay/delivery/srclEarth.deliveryParcels.json
gameplay/overhaul/logistics/parcelModifiers/srclEarthRoad.json
gameplay/overhaul/maps/beamng_earth.json
gameplay/overhaul/phone/apps/srcl-travel.json
gameplay/srcl_earthcareer/homestead_sets.json
gameplay/srcl_earthcareer/kit_canyon_estate.json
gameplay/srcl_earthcareer/kit_culdesac.json
levels/beamng_earth/facilities/srcl_earthcareer.facilities.json
levels/beamng_earth/facilities/srcl_earthcareer.sites.json
levels/beamng_earth/facilities/srcl_earthsidejobs.facilities.json
levels/beamng_earth/facilities/srcl_earthsidejobs.sites.json
levels/beamng_earth/overhaul/start.json
levels/beamng_earth/overhaul/stockStartingModes.json
lua/ge/extensions/srcl/earthCareer.lua
lua/ge/extensions/srcl/earthCareer/config.lua
lua/ge/extensions/srcl/earthCareer/dealer.lua
lua/ge/extensions/srcl/earthCareer/dealers.lua
lua/ge/extensions/srcl/earthCareer/fieldsurvey.lua
lua/ge/extensions/srcl/earthCareer/fuelRegion.lua
lua/ge/extensions/srcl/earthCareer/geo.lua
lua/ge/extensions/srcl/earthCareer/homestead.lua
lua/ge/extensions/srcl/earthCareer/house.lua
lua/ge/extensions/srcl/earthCareer/kit.lua
lua/ge/extensions/srcl/earthCareer/labels.lua
lua/ge/extensions/srcl/earthCareer/layer.lua
lua/ge/extensions/srcl/earthCareer/meter.lua
lua/ge/extensions/srcl/earthCareer/parked.lua
lua/ge/extensions/srcl/earthCareer/places2.lua
lua/ge/extensions/srcl/earthCareer/roadside.lua
lua/ge/extensions/srcl/earthCareer/sidejobs.lua
lua/ge/extensions/srcl/earthCareer/sidejobsPlaces.lua
lua/ge/extensions/srcl/earthCareer/strip.lua
lua/ge/extensions/srcl/earthCareer/survey.lua
lua/ge/extensions/srcl/earthCareer/sweep.lua
lua/ge/extensions/srcl/earthCareer/travel.lua
scripts/srcl_earthcareer/modScript.lua
ui/ui-vue/mods/srcl_earthcareer/RentalPicker.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDesk.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskBuy.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskDealers.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskFlights.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskRent.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskRoadside.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskStay.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskSurvey.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskTaxi.vue
ui/ui-vue/mods/srcl_earthcareer/TravelDeskTaxiThere.vue
ui/ui-vue/mods/srcl_earthcareer/TravelPhone.vue
ui/ui-vue/mods/srcl_earthcareer/travelDeskTabs.js
```

### 1b. Data files built from public-domain sources

**Corrected 2026-11-14:** an earlier draft listed these three as original
work. They are not, and claiming them as such would over-claim in the one
direction that matters — purporting to place a licence over facts nobody
owns.

What is SwimmingRemy's in these files is the **selection, arrangement,
schema and encoding** — the compilation — and that much is offered under
the same terms as section 1. The **underlying facts are public domain**
and this distribution asserts no right over them whatsoever: extract them,
reuse them, relicense your use of them as you wish. Each file names its own
sources in its `source` field, and those names must be kept with the data.

```
gameplay/srcl_earthcareer/airports.json
gameplay/srcl_earthcareer/fuel_regions.json
gameplay/srcl_earthcareer/house_prices.json
```

- `airports.json` — **OurAirports** (public domain), <https://ourairports.com/data/>,
  filtered to scheduled-service airports.
- `fuel_regions.json` — 0.5-degree region cells derived from **OurAirports**
  `airports.csv` (public domain). The US price levels are AAA state averages
  (2026-11-06); the non-US levels are approximate figures written by hand for
  a game, not a dataset and not a live feed.
- `house_prices.json` — US values from the **U.S. Census Bureau** QuickFacts
  (American Community Survey 5-year estimates), a U.S. government work in the
  public domain. Non-US values are approximate figures written by hand for a
  game. **No Zillow, Redfin or MLS data is used or included.**

### 1a. Generated art

Generated art (model, material and texture files authored for this mod).
**Corrected 2026-11-14:** an earlier draft of this file wrongly listed `previews/suburban.png`,
`country.png` and `coastal.png` as screenshots of BeamNG's own buildings. They are not. They are
placeholder cards this mod generates from its own `homestead_sets.json` data — a top-down footprint
diagram with the house, garage and yard boxes — and they are original work:

```
art/shapes/srcl_homestead/skirt/skirt.materials.json
art/shapes/srcl_homestead/skirt/srcl_hstd_skirt.dae
art/shapes/srcl_homestead/skirt/srcl_hstd_skirt.png
art/shapes/srcl_homestead/slab/slab.materials.json
art/shapes/srcl_homestead/slab/srcl_hstd_slab.dae
art/shapes/srcl_homestead/slab/srcl_hstd_slab.png
art/shapes/srcl_homestead/previews/suburban.png
art/shapes/srcl_homestead/previews/country.png
art/shapes/srcl_homestead/previews/coastal.png
```

---

## 2. Covered by CC BY 4.0 — third-party model, modified

Licence: `Creative Commons Attribution 4.0 International`
<https://creativecommons.org/licenses/by/4.0/>

Original work: "American House" by **AleixoAlonso**
<https://skfb.ly/oCWVR>

**This model has been modified.** The changes are itemised in
`art/shapes/srcl_homestead/american/american.CREDIT.txt`, which ships
alongside the files and must be retained in any redistribution. The
original, unmodified model remains available at the link above.
AleixoAlonso does not endorse SwimmingRemy or this use.

These files are **not** covered by the AGPL and **not** covered by the
additional permission in `SRCL-BeamNG-Permission.txt`:

```
art/shapes/srcl_homestead/american/american.CREDIT.txt
art/shapes/srcl_homestead/american/american.dae
art/shapes/srcl_homestead/american/american.materials.json
art/shapes/srcl_homestead/american/tex/aluminum_c.png
art/shapes/srcl_homestead/american/tex/appliance_c.jpg
art/shapes/srcl_homestead/american/tex/brick_c.png
art/shapes/srcl_homestead/american/tex/ceilingwood_c.jpg
art/shapes/srcl_homestead/american/tex/counter_c.jpg
art/shapes/srcl_homestead/american/tex/curtain_c.png
art/shapes/srcl_homestead/american/tex/doorhw_c.jpg
art/shapes/srcl_homestead/american/tex/floor_c.jpg
art/shapes/srcl_homestead/american/tex/foundation_c.png
art/shapes/srcl_homestead/american/tex/garagefloor_c.jpg
art/shapes/srcl_homestead/american/tex/glass_c.png
art/shapes/srcl_homestead/american/tex/kitchencab_c.jpg
art/shapes/srcl_homestead/american/tex/kitchenpanel_c.jpg
art/shapes/srcl_homestead/american/tex/metal_c.png
art/shapes/srcl_homestead/american/tex/plasterceil_c.png
art/shapes/srcl_homestead/american/tex/plasterwall_c.png
art/shapes/srcl_homestead/american/tex/roof_c.jpg
art/shapes/srcl_homestead/american/tex/roof_n.jpg
art/shapes/srcl_homestead/american/tex/siding_c.png
art/shapes/srcl_homestead/american/tex/siding_n.jpg
art/shapes/srcl_homestead/american/tex/windowframe_c.png
```

The preview render of this model is also a derivative of it, and the
same attribution applies:

```
art/shapes/srcl_homestead/previews/american.png
```

---

## 3. The licence and notice files themselves

This file's rule in the header is absolute — an unlisted file is covered by
no grant — so the three legal files that ship with this build are listed
here with their own terms.

```
LICENSE
SRCL-BeamNG-Permission.txt
LICENSES-SCOPE.md
```

- `LICENSE` is the **GNU Affero General Public License version 3**, Copyright
  (C) 2007 Free Software Foundation, Inc. It is reproduced verbatim. In the
  FSF's own words at its head, everyone is permitted to copy and distribute
  verbatim copies of this licence document, but **changing it is not
  allowed**. It is not SwimmingRemy's work and is not covered by section 1.
- `SRCL-BeamNG-Permission.txt` is SwimmingRemy's additional permission under
  AGPL section 7, and must travel with any redistribution of the section 1
  material that relies on it.
- `LICENSES-SCOPE.md` is this file. It must travel with any redistribution,
  because it is what says which terms apply to what.

---

## 4. Called at runtime, not distributed here

The following are **not** included in this distribution. This mod reads
or calls them at runtime if they are present in the user's own
installation. Each carries its own terms, from its own authors, and
nothing in this distribution grants any right to any of them:

- **BeamNG.drive** and everything that ships with it — the engine, the
  career framework, and the level buildings used by the `suburban`,
  `country` and `coastal` house sets. Those buildings are referenced by
  file path and loaded from the user's own game install; no building
  file is bundled here.
- **RLS Career Overhaul** — called at runtime. RLS is separately
  licensed by its own authors, with its own enumerated scope. This mod
  bundles no part of it.
- **BeamNG.Earth** — the level this mod targets, by its own authors.
  Not bundled.

---

## 5. These terms may be refined

This is a beta build. Section 1 is fixed for **this** build: every copy
distributed under these terms keeps them. Later builds may carry a
corrected or expanded version of this file as the licensing of
individual files is reviewed more closely. Where this file and a
specific file's own notice disagree, the file's own notice governs that
file.
