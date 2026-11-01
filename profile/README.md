# hey, we're the bozos 👋

We take PlayStation 2 games and turn them into actual PC programs. No emulator: the game's own code gets
statically recompiled to C++, then we chip away at every bit of PS2 hardware it still leans on until it runs
natively, sound and graphics included.

**No game data in here, ever.** Every port builds from your own disc.

## the ports

| Game | Repo |
|---|---|
| Twisted Metal: Black | [TMB_Recomp](https://github.com/TheBozos/TMB_Recomp) |
| Valkyrie Profile 2: Silmeria | [VP2S_Recomp](https://github.com/TheBozos/VP2S_Recomp) |
| The Lord of the Rings: The Third Age | [TLOTR_TTA_Recomp](https://github.com/TheBozos/TLOTR_TTA_Recomp) |
| Dark Cloud | [DC_Recomp](https://github.com/TheBozos/DC_Recomp) |
| Jade Cocoon 2 | [JC2_Recomp](https://github.com/TheBozos/JC2_Recomp) |
| Soulcalibur III | [SoulCaliburIII_Recomp](https://github.com/TheBozos/SoulCaliburIII_Recomp) |
| Fighting for One Piece | [FightingForOnePiece_Recomp](https://github.com/TheBozos/FightingForOnePiece_Recomp) |
| Smash Court Tennis Pro Tournament 2 | [SmashCourtTennisProTournament2_Recomp](https://github.com/TheBozos/SmashCourtTennisProTournament2_Recomp) |

Screenshots, status and downloads for all of them: **[RecompWatcher](https://thebozos.github.io/RecompWatcher/)**.

## the engine

They all run on our fork of [PS2Recomp](https://github.com/TheBozos/PS2Recomp), originally by
[ran-j](https://github.com/ran-j/PS2Recomp). We've bolted a native renderer, a sound mixer and a pile of
other stuff onto it, and keep ripping out the emulation one piece at a time.

## who

[boubou666](https://github.com/boubou666) and [Arzaroth](https://github.com/Arzaroth), plus a lot of very busy
Claudes.
