# field-lab-results

The built Field Lab, published so it can be opened on a phone:
**https://toob90.github.io/field-lab-results/**

Rebuild an NXL field by placing catalogued bunkers over a layout sheet, then
stand a player on it and see what he can see. Sight is a horizontal cut at eye
height — a bunker you are taller than is not in your way — and a player is
lying, kneeling or standing, which is the one thing about him that decides what
he sees.

Nothing is ranked, scored or counted. Three models that tried all saturated: a
paintball field is mostly open ground, so any yes/no question asked across it
answers yes.

## It is one 3D scene now

The plan view and the 3D view are not two pictures any more. There is one
scene, and every view is a camera on it — including looking straight down. A
body placed from the corner view is the same body, in the same place, as one
placed from above, because there is only one of it.

Each body is a solid built from the same measurements the sight model cuts, so
the picture cannot drift from the answer.

## How it is used

**Drag a bunker or a player out of the dock at the bottom** and let go on the
field. Whatever is picked wears a ring: swing the band to turn it, drag the
body to move it, tap the × to take it away. The second mark is what the thing
is — on a player, how he is standing, and one tap moves him to the next stance;
on a brick, a giant brick or a snake beam, one tap tips it onto its side.

Turning catches on a detent every 15°, and the catch loosens the further out
you reach — so a snake beam can be set to any angle without a modifier key.

Bunkers come in mirror pairs and the two halves are always identical: move,
turn, tip or delete one and the other follows.

**What the pointer lands on decides.** On a body or a player, a drag moves that
thing. On empty ground, a drag drives the camera. From straight above the field
behaves like a map — a drag pans — and tilted it orbits; two fingers always
zoom and pan.

**The cube in the top right** reaches the six views, the twelve edges and the
eight corners between them. On a keyboard, `1`–`6` do the same and `0` fits
what is there.

Drop a layout sheet anywhere on the field to trace over it. It lies on the
ground and is visible from straight above only, fading out as the camera tilts:
a plan image painted on the ground is only true from directly overhead. Drop a
saved `.json` field to open one, and `Ctrl+S` to write one back out.

## What is here, and what is not

This repository holds a **build and nothing else** — one HTML file and the two
asset bundles it loads. The source, the captured layouts, the documentation and
the history live in a private repository.

No layout sheets are published here. A sheet is somebody else's image and is
only ever referenced by file name. A captured layout is opened from your own
disk and saved back to it; it never leaves the browser.

## What it stands on

Ten of the fourteen bunker heights have never been measured against a real
bunker, and five of those sit within five centimetres of a standing eye.
Anything drawn behind one of those bodies rests on a figure nobody has checked.

The way to find out whether it matters is to change the stance and watch what
opens: a body that stops a kneeling eye and not a standing one is a body whose
height is worth doubting. Standing the camera at a corner is the other half of
that — each sight plane is drawn at the height it actually sits at, so a cover
the plane passes over is one you see across, and a cover that stands through it
is one that stops you.
