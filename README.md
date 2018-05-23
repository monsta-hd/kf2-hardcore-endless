# kf2-hardcore-endless
Configs (A, B) (in YML format) + script to convert to *.ini files (+ ini files themselves).

## How to use
To generate *kfzedvarient.ini* file from the YML config simply run, e.g.:
```bash
$ python custom_waves_generator.py zeds_config_A/zeds_config.yml
```
this will create the *.ini file in the same folder as config, and also will print wave names if they are provided.

## Features
* 

## Provided configs
* The first config (A) is more hardcore than the second (B) one, and also with more thoroughly designed waves (in terms of zeds combinations, ratios etc.)
* The second config simply contains all possible "special waves" with increasing complexity, that is waves with zeds of same kind only.
* All waves are possible to complete with a decent team. Note the waves which are called "Crawlers" or similar in the config A still contain zeds of various types/subtypes (like Crawler, Elite Crawler, Alpha Crawler).
* ratio (still contain 10-15% of non-custom zeds).

| Wave | <div align="center">[Config A](zeds_config_A/zeds_config.yml)</div> | <div align="center">[Config B](zeds_config_B/zeds_config.yml)</div> |
| :---: | :--- | :--- |
| **1** | "First blood" | Cyst |
| **2** | "2 surprises" | Slasher |
| **3** | Crawlers | Crawler |
| **4** | Pondemonium prelude | Clot |
| **5** | all 4 bosses (T=1min) | Abomination |
| **6** | Bloats | Stalker |
| **7** | "Alpha wave" | Gorefast |
| **8** | Clots | Rioter |
| **9** | Pondemonium | AlphaSlasher |
| **10** | Hans, 2FPs, Abomination (T=2min) | KingFP |
| **11** | Sirens | EliteCrawler |
| **12** | Husks prelude | AlphaHusk |
| **13** | Gorefasts | Gorefiend |
| **14** | Pondemonium+ | Siren |
| **15** | 2x King{Flesh, Bloat} bosses (T=3min) | Hans |
| **16** | Bloats + Sirens | Bloat |
| **17** | Husks | AlphaStalker |
| **18** | Stalkers | AlphaClot |
| **19** | "All of them" | AlphaCrawler |
| **20** | KING PONDEMONIUM (T=4min) | AlphaPatriarch |
| **21** | "Untypical typical wave" | AlphaGorefast |
| **22** | Scrakes | Quarterpound |
| **23** | Cysts | AlphaSiren |
| **24** | mini-Pondemonium | AlphaBloat |
| **25** | King Bloats (T=5min) | Patriarch |
| **26** | Alpha Pondemonium | Scrake |
| **27** | ????? | Husk |
| **28** | ?????[2] | AlphaScrake |
| **29** | &mdash; | AlphaFleshpound |
| **30** | &mdash; | Fleshpound |
