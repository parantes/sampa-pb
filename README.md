# SAMPA-PB

ASCII Phonetic Transcription System for Brazilian Portuguese

## Purpose

This document describes a [SAMPA](https://www.phon.ucl.ac.uk/home/sampa/index.html)-inspired phonetic transcription system for Brazilian Portuguese (henceforth BP) is presented which has the advantage of being based on a phonological analysis of BP incorporating the notion of archisegment, which makes the notation economical and as cross-dialectal as possible. Like any SAMPA-derived transcription system, SAMPA-PB implements a one-to-one mapping between the [International Phonetic Alphabet](https://www.internationalphoneticassociation.org/content/ipa-chart) (IPA) symbols and ASCII characters, which makes a parser of SAMPA-PB transcriptions easier to implement.

A more complete document describing the SAMPA-PB notation in Brazilian Portuguese can be found in this repository in PDF format.

## IPA to SAMPA-PB mappings

### Full vowels

| IPA | SAMPA-PB | example  |
| --- | -------- | -------  |
| a   | a        | s**a**co |
| ɛ   | E        | s**e**co (verb) |
| ɔ   | O        | s**o**co (verb) |
| e   | e        | s**e**co (adj.) |
| o   | o        | s**o**co (noun) |
| i   | i        | s**i**co |
| u   | u        | s**u**co |

### Reduced vowels

| IPA | SAMPA-PB | example  |
| --- | -------- | -------  |
| ɐ   | A        | sac**a** |
| ɪ   | I        | saqu**e** |
| ʊ   | U        | sac**o**  |
| e̝   | &        | pêss**e**go |
| o̝   | @        | côm**o**do  |

### Onset consonants

| IPA | SAMPA-PB | example  |
| --- | -------- | -------  |
| p   | p        | **p**ata     |
| t   | t        | **t**a**t**a |
| k   | k        | **c**ata     |
| b   | b        | **b**ata     |
| d   | d        | **d**ata     |
| ɡ   | g        | **g**ata     |
| f   | f        | **f**aca     |
| s   | s        | **s**aca     |
| ʃ   | S        | **ch**ata    |
| v   | v        | **v**aca     |
| z   | z        | **z**aca     |
| ʒ   | Z        | **j**aca     |
| h x ɦ χ r | r  | ca**rr**o    |
| m   | m        | **m**ata     |
| n   | n        | **n**ata     |
| ɲ   | J        | **nh**oque     |
| ɾ   | R        | ca**r**o, p**r**ato |
| l   | l        | ga**l**o       |
| ʎ   | L        | ga**lh**o      |

### Phones in coda position

| IPA | SAMPA-PB | example  |
| --- | -------- | -------  |
| ~   | N        | sa**n**to |
| s z ʃ ʒ | 5    | ca**s**ca, a**s**ma  |
| h x ɹ ɻ ɾ | 4  | ca**r**ta, ca**r**ga |
| ɪ̯  | j         | ca**i**xa |
| ʊ̯  | w         | ma**u**   |
| ɐ̯  | 6         | pári**a** |
| e̝  | &         | séri**e** |
| o̝  | @         | mútu**o** |

### Nasal diphthongs

| IPA | SAMPA-PB | example  |
| --- | -------- | -------  |
| ɐ̃ʊ̯̃  | aNw      | m**ão**  |
| ɐ̃ʊ̯̃  | ANw      | bênç**ão** |
| ɐ̃ɪ̯̃  | aNj      | m**ãe**  |
| ẽɪ̯̃  | eNj      | d**e**nte, tamb**ém** |   
| õɪ̯̃  | oNj      | p**õe** |

## Reference

E. C. Albano and A. A. Moreira (1996) Archisegment-based letter-to-phone conversion for concatenative speech synthesis in Portuguese, Proceedings ICSLP’96 Volume 3, 1708–1711.
