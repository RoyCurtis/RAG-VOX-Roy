This is a VOX custom voice for the [Rail Announcement Generator][RAG], for use with the
National Rail phrase and datasets. These are all lines I have recorded with my own voice,
using the VOX Editor.

These clips are post-processed by [SoX][SOX]. They are originally recorded as mono 16-bit
PCM 48000hz WAV files, and then converted to 16000hz 32kbps MP3 files. Command used:

```sh
sox --buffer 2048000 "$1" -C 32 "$2" noisered "../data/vox/noise.profile" 0.4 treble 9 gain -l 4 rate 16k
```

All clips are recorded with a Behringer C-1U USB condenser microphone.

# Usage

To use this voice in Rail Announcement Generator:

1. Click on the gear to open the Settings screen
1. Make sure "Use VOX" is turned ON
1. [Choose "GitHub - Roy" from the voice list][USAGE]
1. Click "Save & close"

Alternatively, you can use the URL `https://roycurtis.github.io/RAG-VOX-Roy` if using the
"Custom" voice.

# License

Please see `LICENSE.md`. This entire work is licensed under the Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 license. This means these voice files are freely
useable and remixable for *non-commercial purposes only*.

# Acknowledgements

For my readings, I have mostly drawn inspiration from Phil Sayer's and Anne's voices, from
official National Rail network systems.

A massive thank you to:

* [Paul Casillas][PAUL], for his recordings of station announcements
* My friends Toby and Kerys, for gifting me a [Welsh pronunciation guide][WELSH]
* [Sir Robrotheram][ROB], for assisting me in the pronunciation of Welsh station names
* [John Ball][JOHN], for his recordings of Welsh place name pronunciations

# Legal

These recordings are meant for use with the Rail Announcement Generator. Please do not
abuse these voice clips, or complete spoken phrases, to impersonate official National Rail
announcements. These clips are not meant for use as a replacement for, or alternative to,
official National Rail announcements.

If you wish to use these voice clips elsewhere, such as for train simulation games, please
feel free. You may email me at roy.adrian.curtis@gmail.com if you are unsure.

[RAG]: https://github.com/RoyCurtis/RAG
[SOX]: http://sox.sourceforge.net/sox.html
[PAUL]: https://www.youtube.com/channel/UC8Hokjo49qLuy3L4bDS5c8w/videos
[WELSH]: https://i.imgur.com/5hTD7tn.jpg
[ROB]: https://robrotheram.com/
[JOHN]: https://www.jlb2011.co.uk/wales/sounds/index.htm
[USAGE]: https://i.imgur.com/lWkOcLS.jpg