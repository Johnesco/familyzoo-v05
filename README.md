# Family Zoo — v05: Containers & Supporters

A backpack that holds things and a park bench that things sit on. Chord distinguishes what is *in* a thing from what is *on* it, and the parser follows.

Step 5 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- `a container` — things go in it
- `a supporter` — things go on it
- Putting a thing inside another at creation time
- How the room description reports contents it did not have to be told about

## The source

The whole step is one file: [`familyzoo-v05.story`](./familyzoo-v05.story) — the step before it plus the ideas above. The chapter that walks through it is [`docs/v05-containers-supporters.md`](./docs/v05-containers-supporters.md).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v05.tests.json
python ../tools/build.py familyzoo-v05 --force
```

## Engine

Pinned to `@sharpee/*` **5.3.0** (Chord 3.6.0), held there by an `overrides` block: 5.3.1 publishes broken subpath exports and breaks `sharpee test`.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
