# Retro Arcade — retrogames4you.github.io

Klassieke pc-spellen die door hun makers vrij zijn gegeven, speelbaar in de browser.
Classic PC games released for free by their makers, playable in the browser.

- DOS games run in [js-dos](https://github.com/caiiiycuk/js-dos) 8.5.3 (GPL-2.0, `vendor/js-dos/`), based on DOSBox.
- Point-and-click adventures run in the [ScummVM](https://www.scummvm.org) web build (GPL-2.0+, `scummvm/`, see `scummvm/NOTICE.txt`).
- In-browser unzip: [fflate](https://github.com/101arrowz/fflate) (MIT, `vendor/fflate/`).
- Game archives are kept unmodified (`games/`, `data/games/`); each entry in `games.json` states its licence.
- Own games run as plain HTML pages in a frame (`engine: "page"`).
- *Under the Loop* (`games/under-the-loop/`) is © 2026 Gunther Donné, all rights reserved. It is not freeware, shareware or open source and is not covered by any licence in this repository: no copying, modification or redistribution without written permission. (Its sound effects are by Kenney, CC0.)
