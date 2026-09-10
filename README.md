# Family Zoo — v05 — Containers & Supporters

Adds intermediate storage: a backpack to put things in, a park bench to set things on, and a fixed feed dispenser. Covers the split between containers and supporters and how capacity limits work.

Step 5 of the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial — a progressive walkthrough of the [Sharpee](https://sharpee.net) TypeScript interactive fiction engine, from a single room to a full multi-file story.

## What this step teaches

- ContainerTrait for things held inside
- SupporterTrait for things placed on top
- Preposition-sensitive parsing of put in vs put on
- Capacity limits via maxItems
- Composing multiple traits (e.g. SupporterTrait + SceneryTrait) on one entity

## Playing

Open `play.html`, or preview the folder:

```bash
python -m http.server 8000 --directory familyzoo-v05
```

## Building

This is a **frozen 0.9.x TypeScript version**. The built player in this folder is the published artifact; it is re-laid from `browser/` by the workspace build:

```bash
python ../tools/build.py familyzoo-v05
python C:/code/ifhub/tools/ship.py familyzoo-v05
```

The authoring tree for every version lives in the [familyzoo](https://github.com/Johnesco/familyzoo) repo.
