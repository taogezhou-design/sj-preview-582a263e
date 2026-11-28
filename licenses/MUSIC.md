# Background music for 山静日长 · 地球 Online · 人生副本

## Current track (from revision 13.7.5)
- Filename: `assets/audio/daylight-wind.ogg` (also `daylight-wind.mp3`, `daylight-wind.wav`)
- Title: Daylight Wind
- Duration: 28-second seamless loop, mono, 22050 Hz
- Character: a light breeze only — airy filtered noise with slow gusts, written to sit under the game at low volume, without a melody or walking pulse

## Provenance
This loop was synthesized for this project on 2026-11-28. It is an original procedural recording (periodic filtered noise with a 7-second and 4-second gust envelope). It does not contain, sample, transcribe, or imitate any third-party soundtrack, including any Genshin Impact / HoYoverse / 米哈游 music, MIDI, or melody.

No third-party audio samples were used.

The earlier loop `daylight-walk` (sine pads, a soft footfall pulse, and filtered noise) remains in `assets/audio/` for the previous revision. It is also original, synthesized on 2026-11-28, and dedicated to the public domain under CC0 1.0.

## License
Dedicated to the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

You may copy, modify, and redistribute the files, even commercially, with no attribution required. Attribution in the player UI is therefore omitted. This file is the project record of source and license.

## Player behaviour
Default volume is low. Playback uses a gapless Web Audio loop of the 28-second buffer (HTML audio is only a fallback). A persistent mute control (localStorage key `sj.bgm.muted`) is shown in the game. Mobile browsers may block autoplay; playback starts on the first tap if needed.
