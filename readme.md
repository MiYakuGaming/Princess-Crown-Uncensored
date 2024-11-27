
# Princess Crown Uncensored Translation GPL edition by 未訳・MiYaku Gaming

This is MiYaku Gaming's script re-write to Uncensor Princess Crown.
I will pull hacked updates from eadmaster's repository for better game functionality when necessary.
I originally forked a very old and outdated version of CyberWarriorX's repository.
SamIAm's Translation was heavily outdated and had many Japanese lines not Translated.
Due to me Translating Princess Crown on YouTube, I received an email to help eadmaster Translate the remaining lines and helped him.
After the remaining lines were Translated, I deleted my old fork, archived it, and forked this repository from eadmaster's repository for my script re-write.
未訳・Miyaku Gaming's Translation will completely replace SamIAm's original Translation(https://github.com/eadmaster/pcrown), use eadmaster's version for SamIAm's Translation(https://github.com/eadmaster/pcrown).
Fans of my Uncensored Translations on YouTube and elsewhere will be happy to know this will be a faithful adaption to the original.
MiYaku Gaming's version restores what was changed in eadmaster's version including profanity, Translation choices and tone of Dialog.

eadmaster leftover:
**P.N.: reportedly CyberWarriorX and SamIAm are still working privately on this project, and since this was forked many years ago it does not reflect the current status of their project. Btw since this was originally released with a GPL-2.0 license, i'd like to exercise my right to keep working on this and make improvements as long as a better translation patch is released.**



## Current status

 - Currently working on Translation Drafts and play-testing to ensure Translations are appropriate in-game too.


## [FAQs](https://github.com/eadmaster/pcrown/wiki/FAQs)


## Preview of eadmaster's version until I get my version moving along

![demo1](https://github.com/user-attachments/assets/b4116a9b-2410-474c-8ad0-a64bc6a2266b)  ![demo2](https://github.com/user-attachments/assets/1b0aebdf-efc6-4c21-9c32-ca81ddf03acd) ![383698647-7a4d755d-de7d-4819-b95d-4aa13da5a572](https://github.com/user-attachments/assets/b46dbcdc-2e41-4dc2-80cd-c29aa6d5eb0d)


## Semi-automated patch instructions

1. obtain a game image matching [these hashes](http://redump.org/disc/4901/), and extract it
2. download and execute one of these easy patching scripts in the extraction dir:
 
  - [for Windows](https://github.com/eadmaster/pcrown/blob/master/src/buildcd/_patch_eng.bat)
  - [for Linux](https://github.com/eadmaster/pcrown/blob/master/src/buildcd/_patch_eng.sh)


## Manual patch instructions for eadmaster's Censored version, it's the only one available to play as of now

1. obtain a game image matching [these hashes](http://redump.org/disc/4901/), and extract it
2. grab the latest xdelta patch from the [Releases section](https://github.com/eadmaster/pcrown/releases).
3. download and install `iat` and `xdelta3`
4. convert track 1 to iso with
`iat -i "Princess Crown (Japan) (1M) (Track 01).bin" -o "Princess Crown (Japan) (1M) (Track 01).iso" --iso`
5. apply the xdelta patch with
`xdelta3 -d -s  "Princess Crown (Japan) (1M) (Track 01).iso"  "Princess.Crown.Japan.1M.Track.01.iso.xdelta"  "Princess Crown (Japan) (1M) (Track 01) (English).iso"`
6. use [this cue sheet](https://github.com/eadmaster/pcrown/blob/master/src/buildcd/Princess%20Crown%20(Japan)%20(1M)%20(English).cue) to play with the patched iso.


## Contributions
 
Issues and PRs are currently restricted to contributors to avoid spamming, trolling, etc.

Contact me via discord or forums if you can contribute or have issues to report (please read the [FAQs](https://github.com/eadmaster/pcrown/wiki/FAQs) first):

 - [Discord](https://discord.com/channels/348545631985467394/797608417857372161)
 - [SegaXtreme](https://segaxtreme.net/members/eadmaster.30323/)
 - [GBAtemp](https://gbatemp.net/members/eadmaster.52646/)

**P.N.: any bit contributed will be re-shared in this repo under the terms of GPL-2.0.**


# New contributors/Special thanks, this applies to this version as well

 - [paul-met](https://github.com/paul-met) and [derek](https://github.com/DerekPascarella) ([short spaces and dialog fixes](https://github.com/eadmaster/pcrown/issues/1))
 - Spike and MLagaffe (bug reports)

