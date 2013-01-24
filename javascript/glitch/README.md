Description
===========
This script simulates the effect of a transmission glitch.

Current version is quite basic:
* upon load of the webpage it calculates glitched frames and loads them into a buffer
* It then plays those frames several times with progressive delays between animations

Current limitations
-------------------
Because it's quite a basic script, it has some limitations.
1. The first animations takes several seconds to occur; cause: frames are being computed.
2. Animation neesds tuning; it's rather raw and not 100% convincing.
3. Animation will consist of the same initial frames [because they are computed only once].


