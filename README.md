# cubase-expression-maps
Expression Maps for Cubase

These are some Cubase expression maps (articulations) I put together for myself for Vienna Symphonic Library.  

These are time consuming to make so if I can help others avoid having to do this, I am happy to share with no strings attached.  If you're really grateful for this, you can                     [buy me a coffee](https://www.buymeacoffee.com/jaredthirsk).

[![Buy me a coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/jaredthirsk)

## See also: a fledgling editor

Mostly for programmers at this point, and it is still partially a manual process and only automates a few things: [cubase-expression-map-editor](https://github.com/jaredthirsk/cubase-expression-map-editor)

## Status

More or less done enough for me: BBO, VI SE.
My next focus: Solo Strings, Strings Pro, Elite Strings, and any BBO I'm missing.

I've done more than this status table indicates, but best to assume the worst.

|     | Series | Instrument | Size | Status |
--- | --- | --- |:---:|:--:|
SY | BBO Hercules | Low brass | | WIP |
SY | BBO Kopernicus | | |  |
SY | BBO Jupiter | | | |
SY | BBO Lyra |  | |  |
SY | BBO Musca |  | |  |
SY | BBO Orion | Flute  | |  |
SY | BBO Orion | Oboe  | |  |
SY | BBO Orion | Clarinet  | |  |
SY | BBO Orion | Bassoon  | |  |
SY | BBO Ymir | Children's choir | |  |
SY | BBO Zodiac | Violin | |  |
SY | BBO Zodiac | Viola | |  |
SY | BBO Zodiac | Cello | |  |
SY | BBO Zodiac | Double bass | |  |
SY | Brass | Trumpets | 4 | ✅ |
SY | Brass | Trumpets | 6 | ✅ |
SY | Elite Strings | 1st Violin | 6 | ✅ |
SY | Elite Strings | 2nd Violin | 5 | " |
SY | Elite Strings | Viola | 4 | " |
SY | Elite Strings | Cello | 4 | ✅ |
SY | Elite Strings | Double bass | 3 | ✅ |
SY | Elite Strings | Tutti compressed | 22 | ✅ |
SY | Elite Strings | Tutti full | 22 |  |
SY | Elite Strings | Octaves | 22 |  |
SYd | Solo Strings | Violin F            | 1 | 92% (wip) |
SYd | Solo Strings | Viola F            | 1 | ✅ |
SYd | Solo Strings | Cello F            | 1 | ✅ |
SYd | Solo Strings | Double bass F  | 1 | ✅ |
SYd | Special Edition | ... | |
SYd | Dimension Strings | ... | |
SYd | Appassionata Strings | Violin | 20 | ? |
SYd | Appassionata Strings | 2nd Violin | 20 |  |
SYd | Appassionata Strings | Viola | 14 |  |
SYd | Appassionata Strings | Cello | 12 |  |
SYd | Appassionata Strings | Double bass | 10 | ✅ |

Heads up: I'm on an old version of Cubase at the moment: 6.0.7.  (I don't know of any changes or compatibility issues with the expression map files.  There's a bug in the expression map editor: if there are a ton of articulations, you cannot drag an articulation below a certain point in the editor.  I'm thinking of upgrading Cubase for the bezier curves in MIDI CC lanes.)

### Abbreviations

 - F - Full (for solo strings, as opposed to basic)
 - SE - Special Edition
 - SY Synchron - recorded for Synchron player
 - SYd Synchronized - recorded for Vienna Instruments and converted for Synchron player
 - SYE - Synchron Elite Strings
 - SYP - Synchron Strings Pro
 - VI - Vienna Instruments

## How to design these?

It can be tricky and there are tradeoffs.

I use directions instead of attributes.

I try to be complete with articulations so that there is a one to one mapping between Cubase articulation and VSL articulation, even though this is a very large number of articulations.  Exception:
 - Dimension strings: player selection

If you want to discuss, contact me via email, create a github issue, or start a thread on [VSL forums](https://www.vsl.co.at/community/forums).

