# Family Zoo — v05: Containers & Supporters

A backpack that holds things and a park bench that things sit on. Chord distinguishes what is *in* a thing from what is *on* it, and the parser follows.

Step 5 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- `a container` — things go in it
- `a supporter` — things go on it
- Putting a thing inside another at creation time
- How the room description reports contents it did not have to be told about

## The source

The whole step is one file: [`familyzoo-v05.story`](./familyzoo-v05.story) — the step before it plus the ideas above. Where it sits in the trail is on the [group page](https://johnesco.github.io/familyzoo/#familyzoo-v05).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v05.tests/
python ../tools/build.py familyzoo-v05 --force
```

## Engine

Pinned in `package.json`, held across the whole `@sharpee/*` scope by an `overrides` block.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
