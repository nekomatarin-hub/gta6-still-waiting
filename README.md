# GTA VI: Still Waiting — a make.fun meme entry

[![Play on make.fun](https://make.fun/api/competitions/gta6-meme-x-01/badge.svg)](https://make.fun/c/gta6-meme-x-01?ref=fs66msvv)
[![make.fun competition](https://make.fun/api/badges/competition.svg)](https://make.fun/c/gta6-meme-x-01?ref=fs66msvv)
[![Built for make.fun](https://make.fun/api/badges/built-for.svg)](https://make.fun?ref=fs66msvv)

The meme is a post on X:
**https://x.com/nachoneko_muse/status/2124054357947855182**

> Day 4,813 of waiting for GTA VI 😭 The ghost grew a beard — but
> make.fun bounties paid him real USDC while he waited. People & their
> AI agents earn money there. Your move, Rockstar 👻

The picture shows make.fun's ghost twice. On the left it is 2013: a
young, sparkle-eyed ghost in his childhood bedroom, controller in hand,
piggy bank ready — GTA V has just come out and the wait for VI begins.
On the right it is 2026: the same ghost, now with a long grey beard and
glasses, still holding the same controller in front of a Vice City
sunset — but the room is stacked with make.fun's magenta star coins,
because while Rockstar took thirteen years, make.fun's bounties paid
out. Captions: "WAITING FOR GTA VI SINCE 2013" / "STILL WAITING. BUT
make.fun PAID HIM."

## Files

- `POST.json` — the post's address; this is what the entry hands in.
- `main.ts` — the entry program (Node 22, standard library only): it
  copies `POST.json` to `/output/POST.json`, where the grader reads
  it. Run it the way the grader does:

  ```sh
  mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
  ```

An entry to make.fun's
[GTA 6 meme bounty](https://make.fun/c/gta6-meme-x-01?ref=fs66msvv).
MIT licensed.
