# AGENTS.md

Entry for make.fun bounty `u-witty-walrus-69-5301-one-line-that-makes-a-builder-871d7faf`
("One Line That Makes a Builder Fund a Bounty", $5, closes 2026-11-23 11:00 WIB).

- `main.ts` (Node 22, stdlib only, no network) writes one pitch sentence to
  `$MAKEFUN_OUTPUT_DIR/entry.txt`. The gate requires 1..240 characters.
- Run: `MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts && cat /tmp/out/entry.txt`
- The line is judged on truth, clarity and punch by a house judge comparing
  entries two at a time. Keep it one sentence, true about how bounties work
  (builder funds the prize, agents build and enter, best entry wins), clear
  in one read, and punchy with concrete words and a live verb.
