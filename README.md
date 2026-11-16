# Remy's Reality — an RLS career on the real world

> ## ⚠ READ THIS FIRST
>
> **THIS IS AN EXPERIMENTAL BETA MOD. IF YOU ARE UNFAMILIAR WITH BEAMNG, RLS, AND BEAMNG.EARTH YOU
> SHOULD RECONSIDER INSTALLING THIS MOD. YOU MAY LOSE OR CORRUPT A CAREER SAVE.**
>
> Back up your career folder before you start, and back it up again before every update. The path and
> the one folder people get wrong are further down this page.

A career add on that lets BeamNG.Earth work with RLS Career Overhaul. Start anywhere on the planet
you like.

**PUBLIC BETA — v0.7.39.** Things will be broken. Please report them.

**You need:** RLS Career Overhaul **2.8.0.1** or newer, BeamNG.drive **0.40.4** or newer, and
BeamNG.Earth **1.9.1-beta.dev.300** or newer — **with BeamNG.Earth's companion server running.**
Wrong versions are the single most common reason a mod doesn't work. Full requirements and the tested
start options are further down.

## Most of RLS's phone apps don't work on Earth — yet

**We're working through them to see how many we can get working.** Most of the ones that fail do so
for the *same single reason*, so fixing it should bring several back at once rather than one at a
time. The list below is where that stands today, and it should get shorter.

RR adds **one** app: Remy's Reality. Everything else on the phone is **RLS's**, and most of RLS's
apps are built around its authored career maps — they look for dealerships, facilities and job sites
sitting at known coordinates on West Coast USA, Italy or Johnson Valley. Earth has none of those.

**Nothing crashes.** Every app below opens. The ones that don't work come up *empty* rather than
erroring or hanging. That is an app asking a question the Earth map cannot answer — not RR breaking
anything and not RLS being broken — so please don't file these as RR bugs.

Don't confuse them with RR features of the same name, either. RLS's **Taxi** app is a job where *you*
drive the cab; RR's taxi is you *calling* one. RLS's **Rentals** is renting your car to a film studio;
RR's rentals are counters you hire a car from. Same words, different feature.

### Work as normal

App Store · Camera · Controls · Gallery · OBD Scanner · Settings · Weather · Wiki — and
Remy's Reality.

### Work, with a catch

| app | what to expect |
|---|---|
| **Real Estate** | You can **sell** an RR home through it. You cannot **buy** — buying land and building is Remy's Reality's Home Builder. |
| **Marketplace** | Sells vehicles you already own. It will **not** let you buy — use Remy's Reality's Dealerships tab for that. |
| **Loans** | RLS's own loans work. RR's property debt is tracked separately and does not appear here. |
| **Bank** | Works, but money RR moves — mortgages above all — is not reflected in it. |
| **Wallet** | Same: it does not track RR mortgages. |
| **Skills** | Works, but only accrues from apps that function, so some trees sit still on Earth. |

RR's money and property not showing in RLS's Bank, Wallet and Loans is **ours to fix, not RLS's**.
It is in Known Issues below. Remy's Reality's own screens are the accurate view of what you owe.

### Empty on Earth

> BeamEats · Car Meet · CarGo · Dakar · Employment · Events · Facility Work · FRE Contracts ·
> Job Broker · Motorsport Events · Off-Road Recovery · Quarry · Racing Team · Rentals · Repo ·
> Road Authority · Taxi · Travel Journal · Tuning Shop

Two of those — **Employment** and **CarGo** — are placed on your home screen by RLS at career start,
so they are the first two you will tap. They are still on the list.

**Dakar** and **Road Authority** are a different case: they belong to RLS's Skeleton Coast map pack
and want that map. They are not an Earth feature and are not going to become one.

**Not yet tested:** Market Watch.

Most of the empty ones share one root cause — nothing can answer *"what businesses are near me"* on
a map with no authored career sites. That work is in progress, so this list should shrink.


> ### Back up your career save before you use this
>
> **SAVES MAY BREAK BETWEEN VERSIONS.** RR writes its own data into your career save. Each version
> tries hard to read the one before it, but no promise is made, and a future version may not be able
> to read a beta save at all.
>
> **Start a new career to try it.** Do not put your 300-hour career in front of it first.
>
> **This is the folder.** Paste it into Explorer's address bar and copy what you find somewhere safe:
>
> ```
> %LOCALAPPDATA%\BeamNG\BeamNG.drive\current\settings\cloud\overhaul\saves
> ```
>
> No `current` folder? Use the version-numbered one (`0.40`). **It is easy to back up the wrong
> thing:** BeamNG's own `cloud\saves` is a different folder holding non-RLS careers, and copying it
> would protect nothing of yours. RLS careers — and everything RR writes — live under
> `cloud\overhaul\saves`.
>
> If you read one line of this page, that one.

---

## Requirements

| | |
|---|---|
| **BeamNG.drive** | **0.40.4 or later.** Built against 0.40.4, verified against 0.40.5. Older versions are not supported. |
| **RLS Career Overhaul** | **2.8.0.1.** Also tested against 2.8.0.2-beta; the test suite runs against both. 2.7.x and below will not work. |
| **BeamNG.Earth** | **1.9.1-beta.dev.300 or later** (Modding API 1.4 or later), **with its companion server running.** |

**Played and tested on BeamNG.Earth dev.450.** *New careers confirmed to start on dev.456.*
BeamNG.Earth moves fast; if something breaks after an Earth update, that is what the compatibility
report is for.

**No part of RLS or BeamNG.Earth is included here.** Both must be installed separately; RR only calls
their public functions at run time.

### Tested one way only

This has been played and tested with **exactly one** set of start options:

| | |
|---|---|
| Difficulty | **Standard** |
| Starting Map | **BeamNG.Earth (Remy's Reality)** — its own entry, not plain BeamNG.Earth |
| Starting Garage | **Random Garage (≤50,000)** |
| Career | **New**, started on Earth |

**Casual and Hardcore difficulty, and the other Starting Garage options, are all untested.** They are not known to be broken — they have simply never been run.

**Hardcore is the one we know will not work as intended:** RR deliberately stands down there, because
RLS's hardcore start grants its own starter vehicle. You will not get the caravan and truck.

**RR is also tested with all of BeamNG.Earth's Experimental features OFF**, which is their default.
Turning any of them on changes the terrain and the buildings RR measures against — **Road steepness
limit**, **Rougher land off the roads**, **Rock faces in deep road cuts**, **Ground over shallow
tunnels**, **Closed 3D models** and **Detailed Canadian lidar** all do. The Home Builder may then
accept or refuse a site differently from the same spot on default settings, and Earth's own panel
warns that first visits load more slowly with any of them on.

## Install

1. Install **RLS Career Overhaul** and **BeamNG.Earth** at the versions above, and
   **start BeamNG.Earth's companion server**. Confirm an ordinary RLS career works
   on a normal map first.
2. **Back up your career save folder.**
3. Download `RemysReality_v0_7_39.zip` from [Releases](../../releases). **Do not unzip it.**
4. **Delete any older `RemysReality_*.zip` from your mods folder.** Two versions installed at once
   is the most common cause of odd behaviour, and nothing warns you about it.
5. Close the game, put the new zip in your mods folder, start the game:
   `%LOCALAPPDATA%\BeamNG\BeamNG.drive\current\mods\`
6. Start a **new** career. Pick
   **BeamNG.Earth (Remy's Reality)** from the **Starting Map** dropdown — *not* plain BeamNG.Earth —
   set **Difficulty** to **Standard** and **Starting Garage** to **Random Garage (≤50,000)**. That is
   the only combination this has been tested with.
7. In RLS's phone, open the **App Store** and install **Remy's Reality**. It is not on the phone by
   default — you install it once and it stays.
8. While you are in there, grab RLS's own **Camera** app if you haven't already — Field Survey
   takes its photographs through it.
9. **Press START in that app when you are standing where you want to live.** Until you do, nothing
   happens — that is by design. See *What it is and how to start* below.

No settings file is needed.

Full instructions, the settings reference and the console commands are in
`README_RemysReality.txt` inside the zip.

> The zip people install comes from the **Release**. The green **Code → Download ZIP** button at the
> top of this page gives you the repository, which is not a mod and will not install.

## What it is and how to start

This is the part worth reading once, because it is unlike any other career mod.

A new career starts **dormant**: BeamNG.Earth behaves exactly as it does with no career at all. Its
own map, its own free teleport, walking, exploring. You have no vehicles yet. Go and explore the
planet, take as long as you like.

Once you are standing where you want to start, open the App Store on the phone. GET the **Remy's
Reality** app and open it. Press **START**. Your Truck and Caravan will spawn. Congratulations, they
are yours! Back your Truck up to the Camper and hitch them together. The caravan is your home, and
your camp plants itself **wherever you are. REMEMBER, you won't get the Garage icon until you unhitch
the Camper** from your Truck.

### Remy's Concierge

Open the Remy's Reality phone app again and a new GUI will pop up. Real businesses at real
coordinates become your dealerships, hotels and rental counters. The tabs, left to right:

- **Hotels** — the nearest real hotels with nightly rates, a taxi or GPS route there, and your
  current stay. During your stay, these also give you a Garage with one parking spot. Anything parked
  there moves to your home garage when you check out.
- **Rent a Car** — every airport and real rental place is a counter. Full-screen picker, a driver
  leaves the car on a road near you, daily billing and a damage deductible.
- **Houses** — **Remy's Home Builder.** Buy land anywhere on Earth and put a house on it by standing
  there and looking at it. Ask whether you can build and you get a yes with the land price, or a no
  with the reason **and the number** — too steep, too close to a building, too near water. Spin the
  house, set its height in inches, press **PLACE HERE**, then choose how to pay. **Nothing is charged
  until you commit and press BUILD.** The ground is never edited; slopes are taken up by a concrete
  foundation skirt, and that will stay true until BeamNG.Earth can bake a pad server-side. Not
  including the Camper, you can own up to **three properties at once**, anywhere on the planet, each
  with its own garage, computer, parking and driveway. This tab sells them too.
- **Flights** — book between real airports, with the career clock advancing by the flight time.
  **4,136 real scheduled-service airports** ship with the mod.
- **Taxi** — call a paid ride. The map's "Go" on foot becomes a taxi fare rather than a free teleport.
- **Car Dealers** — the nearest real car dealers, with GPS routing to them. Click the dealers listing
  to see a list of the available cars. Travel to the dealership to inspect and buy one.
- **Roadside** — Roadside Assistance. Call out a field repair or a fuel delivery to wherever you are.
- **Survey** — **Field Survey.** Paid photo commissions, using the Camera app, on real locations and
  landmarks. The fee grows with how far the next subject is from your last one. Explore and get paid.

### The houses

This build offers four: the **American House**, and three **lore** houses — **Suburban**, **Country**
and **Coastal** — assembled from buildings that are already in your BeamNG install.

Six further designs exist in the mod's data but their models are **not distributed here** while
their redistribution licence is unresolved. A house whose mesh is not present is simply never
offered, so you will not see them.

The three lore houses show stylized placeholder cards instead of rendered previews, because their
meshes live in your game install and cannot be rendered into this mod.

## Known issues

The full list is section 9 of `README_RemysReality.txt` in the zip. The ones you are most likely to
meet:

- **RR's money and property don't show in RLS's Bank, Wallet or Loans.** Those apps read RLS's own
  ledger, and RR writes its property debt separately. Your weekly mortgage is real and is charged —
  it just isn't itemised there. Remy's Reality's own screens are the accurate view. Ours to fix.
- **Only one combination of start options has been tested** — Standard difficulty, the
  BeamNG.Earth (Remy's Reality) map entry and the Random Garage (≤50,000) start, on a new career. Hardcore is known not to grant the caravan
  and truck, by design. Everything else is untested rather than broken; please report what you find.
- **Parked vehicles can be lost after you travel away and come back.** Park somewhere, travel far
  enough that the world re-centres, and the vehicles you left behind can drop out of the world. They
  are **not gone.** Open your camp or home computer, find them in the vehicle list, and use
  **Retrieve** — they come back where you are for a small fee. Save afterwards and their records
  repair themselves. This is the most serious bug in this release; a fix is in progress. Back your
  career up, as above.
- **Your camp stays on the map while you tow the caravan away.** The marker, the fast-travel entry
  and the home computer all remain at the old site until you unhitch somewhere new — so you can
  travel to a camp that is not there any more. Unhitch at your new spot and it moves properly. A fix
  is designed and queued for the next release.
- **The RV dealer is empty on a stock install**, and so is "trade up to a bigger RV". It stocks five
  named configurations and anything whose Body Style is "Motorhome" — and BeamNG ships none of them.
  This is a content gap, not a dealer bug: install a camper or motorhome vehicle mod, or add its
  model to `rvDealerModels`, and the section fills up.
- **Do not place a house during a Beam Vice ride.** (Beam Vice is a separate SR_CL mod — skip this
  if you do not have it.) Both mods take the camera and each puts back the
  one it remembers. A ride that is *driving* is already refused; the case to avoid is a ride that is
  stopped. Nothing is lost if it happens — cancel the placement and your own camera key takes it
  back.
- **If you press START and nothing happens, it probably stood down.** If BeamNG.Earth never loads any
  ground where you are standing, START gives up after 240 seconds rather than dumping you in a city you
  did not choose. It says so on screen and in the diary, nothing is placed, and START works again
  wherever you move to. This is the most likely reason for "I pressed START and nothing happened".
- **Your camp's spot is checked for obstructions, but only roughly.** When your rig is handed over it
  tests the spot for a building and walks the road up to 180 m each way for a clear one. It probes five
  points, not the whole footprint, so something small and awkward can still clip it — and if nothing
  clear is found in that reach it parks at the kerb anyway rather than leaving your career unstartable.
  The diary says which happened.
- **On-foot travel can float you in the sky for up to 20 seconds** on a slow ground load, after the
  screen fade gives up. Cosmetic; the safety hold is what keeps you from falling through the world.
- **Where you start is where you pressed START**, for better and for worse. Press it in a dense city
  and that is where your rig is handed over. RR tests the spot for a structure and walks the road up
  to 180 m each way for a clear one, and tells you if it had to move the rig — but it will not move
  *you*, and it will not pick a quieter place for you.
- **Switching RLS clock kinds** (weather ↔ logistics) rebases a mortgage's paid-until stamp but not
  its missed-payment stamp. A player mid-arrears across a clock switch can have the backlog shrink in
  their favour while the grace clock keeps running. Not fixed yet.

Not yet implemented: remote site checks (you must stand on a site to survey it), more than three
properties, and terrain levelling of any kind.

## Reporting a bug

Please open an [issue](../../issues) — there is a template that asks for the three version numbers
that make a report reproducible.

**A report with a log attached can be answered; one without usually cannot.** The log tag is
`SRCL_EarthCareer`, and RR writes a diary to `/settings/srcl_earthcareer_diag.json`.

## Licence

**RR's own code and data are licensed under the [GNU AGPL, version 3 only](LICENSE)**, with an
additional permission under AGPL section 7 — [`SRCL-BeamNG-Permission.txt`](SRCL-BeamNG-Permission.txt)
— that lets the covered material be combined with BeamNG.drive and the combination conveyed, without
BeamNG's own components becoming subject to the AGPL.

**[`LICENSES-SCOPE.md`](LICENSES-SCOPE.md) is the file that says which terms apply to which files,
and it enumerates them exactly.** No directory-wide inference applies to anything it does not list.
If you redistribute any part of this, that file must travel with it. In short:

- Most of the mod — the Lua, the JSON, the Vue components, the foundation and driveway meshes and
  the three lore preview cards — is SwimmingRemy's, under the AGPL plus that permission.
- **The "American House" model is third-party**, by **AleixoAlonso**, under
  [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), and **has been modified**. The changes
  are itemised in the credit file that ships beside it. It is *not* covered by the AGPL and *not*
  covered by the additional permission. AleixoAlonso does not endorse SwimmingRemy or this use.
- **Three data files are built from public-domain sources** — airports and fuel regions from
  **OurAirports**, house prices from the **U.S. Census Bureau**. The compilation is offered under the
  same terms as the rest; **the underlying facts are public domain and no right over them is
  asserted.** No Zillow, Redfin or MLS data is used or included.
- Place and building data comes from **BeamNG.Earth's** own lookups at run time, which draw on
  **Overture Maps Foundation** data. None of it is bundled.

See [`THIRD_PARTY_NOTICES.txt`](THIRD_PARTY_NOTICES.txt) for the full notices.

BeamNG.drive is a trademark of BeamNG GmbH. This is an unofficial fan project and is not affiliated
with or endorsed by BeamNG GmbH, by the BeamNG.Earth project, or by RLS Modding.
