*⭐**Star this repo if it was useful to you**⭐*

- [Covers Stats](https://github.com/xlenore/ps2-covers#Covers-Stats  "Covers Stats")
- [PSCoverDL App](https://github.com/xlenore/ps2-covers#PSCoverDL)
- [PCSX2 Setup](https://github.com/xlenore/ps2-covers#pcsx2-setup  "PCSX2 Setup")

## Mini-fied PS2 3D Covers

I got tired of constantly needing to go through the process of downloading a new cover, so i decided to try and download the entire repository. Once I did, I noticed a BIG file size difference between them, 8:1. and when i looked closer, I saw that the 2d covers were jpegs, and the 3d covers were png, thats all very well for a couple of games, but for the entire stack, its just not Bonita.

So not only did I trim it down to just the official US titles, (sorry about that, maybe you can copy what i did for your region, or maybe ill get around to just doing the whole thing eventually, but i doubt it), BUT noticed that the PCSX2 program didn't do anything with this transparency, so i figured id fake it with a same colored background. and it works very well.

The process i used to make these, first i had to download the ENTIRE repository, secondly, i thinned out the files to just the us covers to the best of my abilities, then i uploaded them to 2img. and by using the "border" option, with a 1px thickness (0px did nothing) , it changed the base background from black to the very light grey of pcsx2. after that, it was just a simple matter of downloading them and testing them, and finally uploading it here (because i feel like other folks who might be short on space, like me, a steam deck user, would appreciate it)

all told, the final file size comes to about 240mb.

to install these files, navigate to the covers folder, and extract them there directly.

after that youll have the file size benefits of the 2d covers, with the seamless look of the 3d covers. and it should still work with later updates and revisions from the original git

## PSCoverDL

[![](https://user-images.githubusercontent.com/57191159/275665605-4c4b3042-85e4-45b5-8f1b-48a6f00a93ea.png)](https://user-images.githubusercontent.com/57191159/275665605-4c4b3042-85e4-45b5-8f1b-48a6f00a93ea.png)

Small tool to download PS1/PS2 covers for DuckStation and PCSX2.
You can download it from here: [PSCoverDL](https://github.com/xlenore/pscoverdl "PSCoverDL")

## PCSX2 setup

[![](https://i.imgur.com/frOjqhc.gif)](https://i.imgur.com/jTGL0HH.gif)

PCSX2 has its own cover downloader, upgrade to version **v1.7.3329** or higher.
- Open PCSX2
- Tools -> Cover Downloader...
- Use this URL for default covers
  ```python
  https://raw.githubusercontent.com/xlenore/ps2-covers/main/covers/default/${serial}.jpg
- or use this one for 3D covers.
  ```python
  https://raw.githubusercontent.com/xlenore/ps2-covers/main/covers/3d/${serial}.png
- Check "Use Serial Files Name"
- Click Start
- Enjoy :)

## Covers Stats

| Serial |  Available/Total |  Percentage  |
| ------ |  --------------- |  ----------  |
| ALCH | 0/16 | 0.00% |
| CPCS | 0/2 | 0.00% |
| DMP | 0/1 | 0.00% |
| FVGK | 0/2 | 0.00% |
| GUST | 0/2 | 0.00% |
| GWS | 0/1 | 0.00% |
| PAPX | 0/52 | 0.00% |
| PBGP | 0/3 | 0.00% |
| PBPX | 0/47 | 0.00% |
| PCPX | 0/69 | 0.00% |
| PDPX | 0/1 | 0.00% |
| PKP2 | 0/1 | 0.00% |
| PSXC | 0/4 | 0.00% |
| PUPX | 0/1 | 0.00% |
| SCAJ | 0/214 | 0.00% |
| SCCS | 0/20 | 0.00% |
| SCED | 0/492 | 0.00% |
| SCES | 0/485 | 0.00% |
| SCKA | 0/160 | 0.00% |
| SCPM | 0/5 | 0.00% |
| SCPN | 0/9 | 0.00% |
| SCPS | 0/299 | 0.00% |
| SCUS | 208/409 | 50.86% |
| SLAJ | 0/76 | 0.00% |
| SLED | 0/130 | 0.00% |
| SLES | 0/3073 | 0.00% |
| SLKA | 0/446 | 0.00% |
| SLPM | 0/3327 | 0.00% |
| SLPS | 0/1476 | 0.00% |
| SLUF | 0/1 | 0.00% |
| SLUS | 1737/1941 | 89.49% |
| SRPM | 0/1 | 0.00% |
| TCES | 0/14 | 0.00% |
| TCPS | 0/49 | 0.00% |
| TLES | 0/9 | 0.00% |

## Credits
* pcsx2.net
* psxdatacenter.com
* gvcover.top
* imkira3
* waifu2x
* img2
