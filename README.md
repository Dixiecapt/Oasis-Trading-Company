[README.md](https://github.com/user-attachments/files/33421514/README.md)
# Oasis Trading Company Estates 1.4.4

*by Dixiecapt*

The player house at Oasis, put right and made into a trading company's
home: a floor you stand on, a door at its doorway, front steps, a stair to
a paved roof under a canvas awning, and a warehouse beside it with a loft
for an office, which comes with the house. The field behind is planted with
wheat, a dirt drive and paths run round the house, and the tavern's sunk
furniture across the street is lifted back onto the ground.

Everything is measured where it stands each time the game runs, so it fits
with mods that raise or lower the island (Simple Tides, Better Ports).

## Requirements

- Sailwind, BepInEx 5 (installed by Thunderstore Mod Manager / r2modman)

That is all. Optional: **Configuration Manager** (F1) to change settings in
the game.

## Install

Unzip into `BepInEx\plugins\`. You should get:

    BepInEx\plugins\OasisHouseFix\OasisHouseFix.dll

With a mod manager, just install the package.

## What it does

**The house**
- You stand on the floor you see (the stone footing's solid lump a quarter
  metre above it is switched off), and no grass grows through it.
- The door and the house's For Sale sign are carried to the height of the
  doorway.
- Stone steps at the door, as many as the ground there needs.
- The roof logs where they show under the ceiling are cased in wood like
  the window frames (the game paints their undersides a brick red).
- Things kept in the house are put back only once the house is ready after
  loading, so they are not shoved about.

**The roof**
- A masonry stair with a wooden rail up the back wall, and the roof paved
  in brick.
- A canvas awning on four posts over it, open where the stair arrives.

**The warehouse**
- A small gabled barn in the house's own style at the bay-window end: adobe
  walls on a stone footing, a clay-tile roof, the house's own windows, a
  worn tiled floor, a double door for big goods and a loft reached by a
  stair inside.
- A painted sign over the doors: *Oasis Trading Company*, in the game's own
  lettering. Change the words or the font in F1.
- **It comes with the house.** Until you buy the house, its doors stay shut
  and a small *For Sale* sign hangs beside them. Buy the house and the
  doors open and the For Sale sign comes down.
- The ground at that end is levelled, and the house's keeping area is
  stretched over the yard and the warehouse, so things left there are kept
  with the house like things indoors.

**The grounds**
- A dirt drive from the warehouse doors and dirt paths round the house.
- Dirt roads from the house up to the tavern and along its front, round the
  obelisk, out between the trees to the market street, down the market
  street past the stalls, and from the foot of the roof stair to the far
  well.
- The island's dirt roads given a firmer edge (adjustable, 0 leaves them as
  they are).
- The bare field behind the house planted with the island's own wheat, and
  seen from the roof while you are at the house.

**The tavern**
- Tables, chairs and the rumour man standing below the ground are lifted
  onto it.

## Settings

Everything can be switched off or adjusted in F1, or in
`BepInEx\config\com.dixiecapt.sailwind.oasishousefix.cfg`. The sections are
House, Roof, Warehouse, Grounds, Field and Tavern, and General has a master
switch. The roads round the house are one switch in Grounds. In the
Warehouse section you can change the sign's words and font and slide the
warehouse a little if another mod has something in its way.

**Keep each house save number** (House, on by default): some mods give an
anchor or mooring rope the save number of a player house, and a save with
anything left in that house then stops on its loading screen. This keeps
the houses' numbers clear. A save made this way still loads without the
mod.

## Taking it out

Move your things out of the warehouse and the yard first: without the mod
the warehouse is not there and that ground is no longer kept with the
house.

## Version history

- **1.4.4**: first shared release, as Oasis Trading Company Estates
  (the test builds before it were called Oasis House Fix).
