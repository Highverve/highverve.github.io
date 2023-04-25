---
title: Procedural Language Generation Library
layout: default
filename: plgl.md
---


![PLGL logo](https://raw.githubusercontent.com/Highverve/PLGL/master/icon.png)

# Procedural Language Generation

*Procedural Language Generation Library* (PLGL) is a code library designed for game developers who want consistent, fictional languages for their game's cultures and peoples, without the time needed to create one. The language author constructs the alphabet, letter groups, syllable structures, affixes, character filtering for sentence deconstruction, and other constraints; then, the generator processes a regular sentence, and returns a new, stylized sentence from your fictional language.

---

## Examples

*Qen* is more of a scandinavian/english language, whereas *Jabanese* attempts to mimic Japanese. Qen has complex syllables, and a moderate amount of exclusion rules. Jabanese has simpler syllable structures, yet relies on letter exclusion a bit more.

In English:
```
So in this pleasant vale we stand again,
The field of Enna, now once more ablaze
With flowers that brighten as thy footstep falls
```

In the fictional language called *Qen* (with seed offset at 2):
```
Fras sil iren yadïnem nigüŋ mel spil nälis,
Lo flapäs ha Enna, om kelbu nölën numëmo
Nob sallesen on sölez egel hän borsüspöŋ ŝlonen
```

Qen, this time with the seed offset at 15:
```
Ik öl fonen mëöbür femöm füp be fume,
Lo manäs ha Enna, saŋ nebö fökum belidëf
Fe skenälen sof ürur egel ü mërrublan ëlen
```

Now in a fictional Japanese language (seed offset at 6 — Romaji and Hiragana):
```
pa mene ta wadagomo sudere ba ki musaha、
ぱ めね た わだごも すでれ ば き むさは、

chusa kugucho giyu gita、 shoku kazubi dayuke kozopeyo
ちゅさ くぐちょ ぎゆ ぎた、 しょく かづび だゆけ こぞぺよ

sote pumaya shu sushorya chi muki pobihe na。
そて ぷまや しゅ すしょりゃ ち むき ぽびへ な。
```

---

For more information on this code library, **[click here](https://github.com/Highverve/PLGL)**.
