# v05 — Containers & Supporters

A backpack that holds things and a park bench that things sit on. Chord distinguishes what is *in* a thing from what is *on* it, and the parser follows.

## What this step adds

- `a container` — things go in it
- `a supporter` — things go on it
- Putting a thing inside another at creation time
- How the room description reports contents it did not have to be told about

## The source

The whole step is one file: [`familyzoo-v05.story`](../familyzoo-v05.story). Read it top to bottom — it is the previous step plus what is listed above.

## Running it

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v05.tests.json
```

Chord language reference: <https://sharpee.net/chord/>
