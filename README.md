# My MPV config (uosc skin with QoL edits)

There are a few nice keybinds, the rest you can check in input.conf - they have comments (mostly)

ctrl+x - to cut a fragment from a video (you must have ffmpeg installed and added to the PATH in Windows). And it works only when there is a track with EN subtitles and JP soundtrack (it's a config to clip anime), you can easily edit it tho just remove `-disposition:s:0` and `-map 0:v -map 0:s:0 -map 0:a:m:language:jpn` from `slicing.lua`

alt+z - jump to the next silence (useful when skipping openings that are not marked)

Added nice default subtitle styles that you can force using `u` key.

z/Z - scroll through chapters

Shaders under CTRL+1-6 (Anime4K)

CTRL+F - jump to a specific given time

F12 - help menu or command finder xD

Entire UI pops up on pause and hides on play

Flash timeline for a second on forward/backward

No black boxes for title and speedmeter

Shows mouse all the time when paused, hides when playing

Thumbnail script installed
