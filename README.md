# Dance with Lulu

An animated website that teaches kids eight beginner dance moves. Lulu, a cartoon girl in a pink shirt and purple tutu, dances each move on a little stage with counts, music and footprints. Everything is in `index.html` with no dependencies (it uses the Fredoka and Nunito fonts from Google Fonts).

It's built the same way as [Back Exercises](https://github.com/kgram1989/Back-Exercises): one file, an SVG figure posed with inverse kinematics, cards you can play, and a guided mode with a spoken voice.

## The moves

| # | Move | Level |
|---|------|-------|
| 1 | Step-Touch | Easy |
| 2 | Bounce & Clap | Easy |
| 3 | Sway & Wiggle | Easy |
| 4 | Rainbow Arms | Easy |
| 5 | Disco Point | Medium |
| 6 | Grapevine | Medium |
| 7 | Star Jump | Medium |
| 8 | Ballerina Twirl | Tricky |

## Features

- **Move cards**: each one shows the move's main pose. Press play to watch Lulu dance it to an 8-count. A count bubble and beat dots show where you are, the current step is highlighted, and orange footprints and arrows show where her foot goes next. Coloured trails follow her hands, and claps, toe taps, jumps and spins get little effects.
- **Countdown**: every move starts with "3, 2, 1, Go!" so kids can get ready.
- **Dance Party**: plays all eight moves in a row, full screen, with music, spoken cues ("Next up: Grapevine!", "Last time!"), Back / Pause / Skip, and confetti at the end. It keeps the screen awake.
- **Music**: a cheerful beat (kick, clap, hi-hat, bass and arpeggio) generated in the browser with Web Audio, so there are no audio files and no copyrighted music.
- **Settings**: speed (Slow 72, Medium 92, Fast 112 beats per minute) and repeats (2, 3 or 4 eight-counts of each move).
- **Sticker book**: earn a sticker for each move by pressing "I can do it!" or by dancing it in a Dance Party. Gold stars mark the days you danced this week.
- Light and dark themes, works on phones (including sideways), and respects "reduce motion".

Settings and stickers are stored only in the browser on your device.

## Lulu's Big Dance (`routine.html`)

A full two-minute routine, taken step by step from a group dance video and danced by Lulu from start to finish. It has about 20 parts, each a few counts long: a dive and curl, side stretches, kneeling poses, knee lifts, heel-kick jogs, points, a turn, skips, hop kicks, squats and a ta-da finish.

- **Player**: play, pause, restart, a scrubber with marks for each part, and speeds of Slow (½), Medium (¾) and Real speed.
- **Cues**: big words say what to do now and small words say what's next. The count bubble shows 1–8 once the beat starts.
- **Parts list**: tap any part to jump to it and practise it.
- **Mirror**: flips Lulu so her left matches yours.
- **Music**:
  - *Lulu's beat* is an original groove made in the browser at the routine's tempo (160 beats per minute). It's soft for the slow opening and full from 0:24.
  - *My video* plays your own copy of the dance video or song from your device, and Lulu follows it to the second. The file is never uploaded, and the song itself isn't included in this repository. Use **Earlier / Later** if a different copy of the song starts at a different point.

## Deploy with GitHub Pages

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, then **Save**.
3. After a minute the site is live at `https://kgram1989.github.io/Dance-with-Lulu/`.
