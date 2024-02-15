# GG2 Overture Pink Sol
have you ever wanted Sol Badguy in GG2 Overture to be pink? No? Too bad.

# Installation
Replace TD220.PKM in the data folder in the root of GG2 with TD220.PKM in this repo. You can also replace TD221 and others to make palettes other than red be pink.

# Credits
me, jillscrungus on GitLab (https://gitlab.com/backyardtools/overture/)

# How this was done
Hue -20 with the Hue/Saturation parameter in GIMP for everything but Sol's skin, then packed into a PKM with ```python ~/prototypes/unpkm.py -vf -t 3 TD220/ -o TD220.PKM``` on all textures within TD220.PKM
