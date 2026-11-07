# Contributing

These are the defaults for every repo in The Bozos. If a repo has its own `CONTRIBUTING.md`, that one
applies instead.

## No game data

Don't post, commit or link to any of these, in code, issues, pull requests or logs:

- disc images, ELFs, IRX modules or other files from a game
- BIOS files or keys
- code generated from any of the above

Don't ask where to find them either. Every port builds from the player's own disc, and we want to
keep it that way. Disc serials and file hashes are fine.

## Where things go

- **A problem in one game:** open an issue on that port's repo. If you think the engine is at fault
  but aren't sure, start there anyway.
- **A problem in the engine itself:** open an issue on
  [BozoEngine](https://github.com/TheBozos/BozoEngine). Our PS2Recomp fork has issues turned off, so
  report problems with PS2Recomp-based ports on the port's repo.
- **Questions and ideas:** a blank issue on the repo it concerns is fine.

## Pull requests

1. Open an issue first for anything bigger than a small fix, so nobody builds something we can't
   merge.
2. Keep a pull request to one topic.
3. Say what you tested: which game, and how far you got in it.
4. Make sure CI is green, if the repo has it, and follow the commit style in the repo's history.

## BozoEngine is clean room

Nothing in BozoEngine is copied from PS2Recomp or any other project, not even a single line. Code is
written from the specs in `docs/specs/`, and third-party libraries are used as dependencies under
their own licences. The full rules are in
[section 6 of the plan](https://github.com/TheBozos/BozoEngine/blob/main/docs/PLAN.md#6-clean-room).
