<p align="center">
  <img src="https://raw.githubusercontent.com/TheBozos/.github/master/assets/banner.png" alt="The Bozos: PS2 recompilation, boubou666 and Arzaroth" width="100%">
</p>

# hey, we're the bozos 🤡

We take games and turn them into actual PC programs. No emulator and no compromise.
The game's own code gets statically recompiled to C++,
then we chip away at every bit of PS2 hardware it still leans on until it runs
natively. 

Every port builds from your own disc. We don't want ninjas to stomp at our doors.
Ninjas and clowns... would you imagine?

## the ports

| Game | Repo | Current state |
|---|---|---|
| Twisted Metal: Black | [TMB_Recomp](https://github.com/TheBozos/TMB_Recomp) | Playable, full speed, native ([0.3.2](https://github.com/TheBozos/TMB_Recomp/releases/latest)) |
| Valkyrie Profile 2: Silmeria | [VP2S_Recomp](https://github.com/TheBozos/VP2S_Recomp) | Playable (chapter 1) |
| The Lord of the Rings: The Third Age | [TLOTR_TTA_Recomp](https://github.com/TheBozos/TLOTR_TTA_Recomp) | Playable to the first battle |
| Dark Cloud | [DC_Recomp](https://github.com/TheBozos/DC_Recomp) | Bring-up |
| Jade Cocoon 2 | [JC2_Recomp](https://github.com/TheBozos/JC2_Recomp) | Bring-up |
| Soulcalibur III | [SoulCaliburIII_Recomp](https://github.com/TheBozos/SoulCaliburIII_Recomp) | Playable, in testing |
| Fighting for One Piece | [FightingForOnePiece_Recomp](https://github.com/TheBozos/FightingForOnePiece_Recomp) | Playable |
| Smash Court Tennis Pro Tournament 2 | [SmashCourtTennisProTournament2_Recomp](https://github.com/TheBozos/SmashCourtTennisProTournament2_Recomp) | Playable |

Screenshots, status and downloads for all of them: **[RecompWatcher](https://thebozos.github.io/RecompWatcher/)**.

## the engine

They all run on our fork of [PS2Recomp](https://github.com/TheBozos/PS2Recomp).
We've bolted a native renderer, a sound mixer and a pile of
other stuff onto it, and keep ripping out the emulation one piece at a time.

## who

[boubou666](https://github.com/boubou666) and [Arzaroth](https://github.com/Arzaroth), plus a lot of very busy
Claudes. All coordinated via [a very advanced communication protocol](https://github.com/Arzaroth/c2c-conv).
