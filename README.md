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

## How it is used

Drag a bunker or a player out of the strip at the top and let go on the field.
Whatever is picked wears a ring: drag the ring to turn it, drag the four arrows
to move it, tap the × to delete it. The fourth mark is what the thing is — on a
player a figure of how he is standing, which opens into lying, kneeling and
standing; on a brick, a giant brick or a snake beam, the body itself, and one
tap tips it onto its side.

Bunkers come in mirror pairs and the two halves are always identical: move,
turn, tip or delete one and the other follows.

Drag the field itself to move the view. Drop a layout sheet anywhere on the
field to trace over it, or drop a saved `.json` field to open it. The switch in
the corner turns the whole picture into 3D, which is where the heights are
visible; it turns through the four corners of the field and is read-only.

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
height is worth doubting. The 3D view is the other half of that — it draws each
sight plane at the height it actually sits at, so a cover the plane passes over
is one you see across, and a cover that stands through it is one that stops you.
