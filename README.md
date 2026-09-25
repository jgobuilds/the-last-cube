# The Last Cube

*A fun AI project between a father and son, learning AI together.*

**Play it: https://jgobuilds.github.io/the-last-cube/**

<img src="play-qr.png" width="160" alt="QR code for https://jgobuilds.github.io/the-last-cube/">

Scan it with a phone or tablet camera to play.

A blocky beat-'em-up. Your friend has been taken - fight through six levels,
beat six bosses, and save them. Sword up close, bow for the Sky Biters that
fly out of reach.

## How to play

| Keyboard | Arrow keys | Tablet / phone | Does |
| --- | --- | --- | --- |
| W A S D | arrows | joystick (left thumb, anywhere) | Move |
| J | Z | big sword button | Sword - tap for a three-hit combo |
| K | X | roll button | Roll - you can't be hit mid-roll. Hold up or down to roll that way |
| L | C | bow button | Bow - tap to fire; walk over fallen arrows to pick them up |
| I | V | special button (pops up when ready) | Your hero's special move - hold up or down to aim it |
| Space | Space | star button (pops up when ready) | Turn into the Super Knight when the meter is full |
| Esc | | pause button | Pause - shows every move you know, and Quit to title |

A game controller works too.

## Install it like an app

Open the game in the browser, then:

- **iPad or iPhone (Safari):** tap Share, then **Add to Home Screen**.
- **Android (Chrome):** tap the menu, then **Install app** (or **Add to Home screen**).
- **Computer (Chrome or Edge):** click the install icon at the right-hand end of the address bar.

It gets its own icon, opens full screen like any other app, and keeps
working offline once it has loaded. New versions arrive by themselves the
next time it opens.

**To leave:** pause, **Quit to title**, then **Exit** (top left of the
start screen). Some tablets do not let a web app close itself - then Exit
shows how instead: swipe up from the bottom edge on an iPad or iPhone,
swipe back or press Home on Android.

## Things to know

- **New moves arrive as you go:** the bow when the first Sky Biter shows
  up, your hero's special after the first boss.
- **Two heroes, two styles.** Leif's **Shield Lunge** charges in behind his
  shield; Rose's **Whirl Away** spins her back out of danger, hitting
  everyone around her. Each hero has their own path of upgrades.
- **Watch the floor.** Yellow stripes show where an attack will land. Roll
  through them just as it hits for a **PERFECT** dodge.
- **Stars.** Up to three per level - the three goals sit in the top right
  as you play. Can you get all 18?
- **Take a bad guy's power.** Grab the glowing orb some of them drop.
- **Rewards after every boss** - and rare gold cards with new powers.
- **Gems** go in the bank for the shop, even if you lose.
- **Survival** and the **Wardrobe** (skins, hats and capes) open up once
  you've saved your friend.
- Every level hides one golden cube...

## What we learned

We made this together - the two of us and an AI coding agent (Claude Code).
Along the way we found five habits that make building with AI go much
better.

**1. Give the agents context.** The AI starts every session knowing nothing
about the project, so the project keeps a notes file just for it
(`CLAUDE.md`). It holds the one rule that matters most - a new bad guy has
to be a change to a data file, never to code, so the designer of the two of
us can add them himself. It also says how the code is laid out, and lists
every mistake already paid for. Whenever the AI learns something the hard
way, it goes in the notes, so no session has to learn it twice.

**2. Test, and give feedback.** Nearly 500 automatic checks play the game
far faster than we can and fail loudly when a change breaks something. A
screenshot tool lets the AI *see* what it made, and a robot player runs
every level on every difficulty to prove each one can be beaten. The best
feedback still came from playing it: "the green knight blends into the
grass", "the secret is where swinging ends the level", "a dash AND a lunge
is confusing". One sentence each - and each one a real fix.

**3. Research best practices before designing.** How long a boss takes to
wind up an attack comes from research on children's reaction times, not a
guess. We borrowed from games that had already solved our problems -
stealing a bad guy's power, like Kirby; picking rewards between bosses,
like a roguelike - and ran a UX review, which found words sitting on top of
the fighting and far too much to read.

**4. Turn it into a skill so it's repeatable.** Anything done more than
once became a tool or a written step-by-step: building and publishing the
web version, taking screenshots, checking for personal information before
anything goes public. One step instead of a list to remember - for us and
for the AI.

**5. Scan the market before building.** Before making something, look at
what already exists. We used a free game engine (Godot) instead of writing
one, free hosting (GitHub Pages) after comparing a few, and a ready-made
QR-code library for the code at the top of this page.

Made with [Godot](https://godotengine.org).
