# Wine-vst

This is a collection of some VSTs tested under Linux with [Wine](https://www.winehq.org/) and [LinVst](https://github.com/osxmidi/LinVst).

All the reported VSTs were tested in [Reaper](https://www.reaper.fm/), with the indicated Wine versions (However, all the versions of Wine higher than the reported ones SHOULD work as well, pease report if you find out this is not the case).

If you would like to add one or more VST to the list or if you find anything wrong in it, open an issue or communicate your opinion in the [Reaper forum](https://forum.cockos.com/showthread.php?t=217855). Remember to indicate the Distro and the Wine version you're using.

NOTE: This list will never be complete, neither reagarding the tested distros and the Wine versions, nor the tested plugins. The main purpose of this list is to give you an idea about what you can expect to get working with LinVst, without messing with your system (If you're not using a completely unknown distro, in which case you may consider switching to something more popular).

## Tested VSTs

* Multiple reported Wine versions (e.g. 4.0-4.2) indicate that the VST was tested from the former version to the latter.
* ✔ indicates a fully working plugin
* ● indicates a working plugin, with minor issues
* ✘ indicates the presence of some critical issues that make the plugin unstable/unusable

| VST | Working | Details | Tested Distros | Tested Wine Versions |
| --- | :---: | :---: | :---: | :---: |
| Alesis Microverb | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Amplesound Ample Bass P Lite II | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Amplesound Ample Guitar M Lite II | ● | No MIDI drag and drop| Linux Mint Debian 3 | 4.3 |
| Arturia Minimoog V | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Arturia V Collection | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Audio Assault BassGrinder Free | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault Defacer | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault FilterCrusher | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault Grind Machine II | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault Head Crusher | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault The Punch | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault Transient | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault Winchester | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| Audio Assault Druminator | ✔ | Fully Working | Ubuntu Studio 18.10 | / |
| CK_Modules X-Jupitae Flexoid | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| CK_Modules X-Jupitae Wide-Boy | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Clone Ensemble BassChorus | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Creative E-MU Proteus VX | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| DVS Guitar | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| DVS Saxophone | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| HoRNet SW34EQ MK2 | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Graffio | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Tape | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Spaces | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet AnalogStage | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet DeeLay Plus | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet LU Meter | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet ThirtyOne | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Angle | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet TrackUtility MK2 | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet ElliptiQ | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Guitar Kit | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Dynamics Control | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet ChannelStrip MK3 | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet ELM128 | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet TrackUtility | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet Magnus MK2 | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| HoRNet VU Meter MK3 | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Ignite NadIR | ✔ | Fully working | Arch Linux, Ubuntu 18.10 | 4.0-4.2 |
| Ignite NadIR 2 | ● | Some graphical glitches (d2d1.dll) | Arch Linux, Ubuntu 18.10 | 4.0-4.4 |
| Ignite Emissary 1-2 | ● | Some graphical glitches (d2d1.dll) | Arch Linux, Ubuntu 18.10 | 4.0-4.4 |
| Ignite TPA-1 | ✔ | Fully working | Arch Linux, Ubuntu 18.10 | 4.0-4.2 |
| IK Amplitube 4/Custom Shop | ✔ | Fully working | Arch Linux, Ubuntu 18.04, Ubuntu 18.10 | 4.0-4.4 |
| iZotope Ozone 8 | ✘ | Doesn't run | Ubuntu 18.04 | 4.0 |
| Klanghelm MJUCjr | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| LePou Amp Pack (all sims) | ✔ | Fully working | Arch Linux, Ubuntu 18.04, Ubuntu 18.10 | 4.0-4.4 |
| LePou LeCab (32 bit) | ✘ | Freezing, Unusable | Arch Linux, Ubuntu 18.04, Ubuntu 18.10 | 4.0-4.4 |
| Lexicon Pantheon Reverb | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Native Instruments Kontakt 5 | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Native Instruments Guitar Rig | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Native Instruments B4 Organ | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Native Instruments FM7 Synth | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Native Instruments FM8 Synth | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| One Small Clue Grace Sampler | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Overloud TH3 | ✔ | Fully working | Arch Linux | 4.2 |
| Plugin Alliance Brainworx bx_rockrack V3 Player (Free presets) | ✔ | Fully working | Arch Linux | 4.2 |
| Positive Grid BIAS FX | ✘ | Serious GUI issues | Arch Linux | 4.2 |
| PSP Vintage Warmer | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Spitfire Audio Peel Guitar | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Spitfire Audio Strings | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Stillwell Audio The Rocket | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Synthedit Davo Synth | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit eSline ARP String ensemble | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit MicroMoon MicroMoog | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit SxMJune Juno synth | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit MoonSonoSX | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit NanoTron Mellotron | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit ODsay ARP Odyssey | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit OR2V Oberheim TVS | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit Mr. Ray 73 Rhodes | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit Mr. Tramp Rhodes | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Synthedit Jazz Baby Grand | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| TBProAudio dpMeter3 | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Tokyo Dawn TDR Nova | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Toontrack EZDrummer 1 | ● | No drag and drop | Ubuntu 18.04, Ubuntu Studio 18.10 | 4.0 |
| Toontrack Superior Drummer 3 | ✘ | No activation, No presets, GUI issues | Arch Linux | 4.2 |
| Toontrack EZkeys Piano Essentials | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Toontrack Drumkit From Hell Superior | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Toontrack Superior Drummer 2 | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| TSE X50 | ● | Free version only (Registration doesn't work) | Arch Linux | 4.2 |
| Vacuumsound ADT | ✔ | Fully working | Ubuntu 18.04 | 4.0 |
| Valhalla Vintage verb | ✔ | Fully working | Fedora 29 | 4.0 |
| Variety Of Sounds Plugin Suite | ✔ | Fully working | Linux Mint Debian 3 | 4.3 |
| Vember Audio Shortcircuit 1.1.2 | ✘ | Not finding/loading samples | Ubuntu 14.04 | 2.0 |
| Voxengo FREE Plugins | ✔ | Fully working | Ubuntu Studio 18.10 | / |
| Voxengo Elephant | ✔ | Fully working | Fedora 29 | 4.0 |
| Yohng W1 Limiter | ✔ | Fully working | Ubuntu 18.04 | 4.0 |

Be aware that your experience can greatly vary depending on which plugin you're using, but in some cases it's possible to achieve very good results through Wine and LinVst.

Apparently the biggest issues usually concern the GUI (as confirmed by osxmidi himself) and the license activation/registration, while the sound processing works fine in general.

(Interesting fact: On my laptop, with a i7-6500u and a Behringer UMC204HD audio interface, I actually get less drop-outs running Amplitube 4 in Reaper through LinVst than I do on a native Windows 10 installation with the latest specific ASIO drivers)
