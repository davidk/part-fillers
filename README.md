# Part Fillers!

This is a public repository containing a list of what you can buy when shipping charges feel like they're a bit
much for what little you are ordering. Add more stuff!

As this is version controlled, feel free to fork, add your own, and send a pull request to incorporate stuff. Tables in
Markdown are pretty easy. Need help? Add to the issues list (to the right).

Random notes: Bottom of the basement stuff is avoided where possible/known. No point in buying crappy stuff; it'll
just get thrown away for better parts or blow up stuff down the line. If you see something more cost effective
(with decent quality); please feel free to add/replace.

### Headers (0.1"/2.54mm)

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| 2.54mm/0.1" header (TH) | 36 pins/positions | [649-68004-236](http://www.mouser.com/ProductDetail/FCI/68004-236/?qs=eanFghet1JOyyJ/RYv6JvQ==) | |

### Resistors

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| 10k ohm resistors (TH) | Common use for pullups/pulldowns | *[Note R1-M]*: [291-10K-RC](http://www.mouser.com/Search/Refine.aspx?Keyword=Xicon+291-10K-RC) | |

[R1-M]: Can do other values by entering 291-VALUE-RC -> [291-330-RC = 330](http://www.mouser.com/Search/Refine.aspx?Keyword=291-330-RC) or [291-1K-RC = 1k](http://www.mouser.com/Search/Refine.aspx?Keyword=291-1K-RC)

### Capacitors

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| 0.1uF capacitors | Sprinkles for your circuits | *Vishay X7R 10% [Note: C1]* [594-K104K15X7RF5TH5](http://www.mouser.com/ProductDetail/Vishay-BC-Components/K104K15X7RF5TH5/?qs=CuWZN/5Vbiofhf%252buZNGw/g==) | |

[C1]: Vishay X7R 10%: X = -55c :: 7 = +125c :: R = +/- 15% = (15% capacitance change over -55 to +125c)

### Diodes

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| 1N4001 | Mostly used for power stuff | *Fairchild* [512-1N4001](http://www.mouser.com/ProductDetail/Fairchild-Semiconductor/1N4001/?qs=PKwgOmPR8%252bnXpabSf4kJpg==) | |
| 1N5817 | Schottky: for most of your fast switchin' and LFVD needs | *STMicro* [511-1N5817](http://www.mouser.com/ProductDetail/STMicroelectronics/1N5817/?qs=sGAEpiMZZMtQ8nqTKtFS%2fD9SVzsgHTKGsrEMHLFTAoc%3d) | |

### Microcontrollers

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| ATtiny85 (DIP-8) | Loads of fun and possiblities in a small DIP-8 package | [556-ATTINY85-20PU](http://www.mouser.com/ProductDetail/Atmel/ATtiny85-20PU/?qs=8jWQYweyg6NCiiaOb5GI9Q==) | |

### Transistors/BJTs

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| 2N3906 ***(PNP)*** | For the 2N3906 between TF and TFR, [TFR is 0.08 while TF is 0.20](http://www.mouser.com/Search/Refine.aspx?Keyword=512-2N3906TF) as of 5/15/2013 | [512-2N3906TFR](http://www.mouser.com/ProductDetail/Fairchild-Semiconductor/2N4401TFR/?qs=hXzPkG2nhVb/HW5tAgoYwg==) | 
| 2N3904 ***(NPN)*** | TF/TFR is a packaging designation, they're both tape reel based | [512-2N3904TF](http://www.mouser.com/access/?pn=512-2N3904TF) | | 
| PN2222A ***(NPN)*** | With wound toroids, can be used to make joule thieves -- lots of theory in a practical package! | [512-PN2222ATA](http://www.mouser.com/ProductDetail/Fairchild-Semiconductor/PN2222ATA/?qs=QwEULm8S1DrfA/CRPqYa%252bw==) | |

### Power

| Part | Description/Notes | Mouser | Digikey |
|-------|-----------------|-----------|------------|
| LM7805 5V 1A linear regulator | Don't forget the caps ([datasheet [pdf] has applications](http://www.mouser.com/ds/2/149/LM7805-189995.pdf)) | [512-LM7805CT](http://www.mouser.com/ProductDetail/Fairchild-Semiconductor/LM7805CT/?qs=cnIeywgme7bzmZ37/iFT9w==) | |
| 2.1mm DC Power Jack | Pretty common jack size (rated for 18V DC @ 1.5A) | [163-179PH-EX](http://www.mouser.com/access/?pn=163-179PH-EX) |  | 
