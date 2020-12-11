# newDeedsMusicIcon

### How to implement this icon
1. In skins.css, replace everything before `:root` apart from the first line with the contents of `redoMusicIcon.css`
2. Upload the font `BravuraText.otf` to your `/fonts` directory on DEEDS
3. Change the class of the `<a>` link that leads to the Music Timetable from `icon-podcast` to `icon-music`

### How to show music lessons on the timetable page (assuming you have done the above)
1. For every music lesson the student has, go to the `<div>` with `class="timetable-subject"` and insert a sibling `<div>` before it with `class="icon-music-lesson"` and inside it put the unicode symbol [`\266b`](https://www.codetable.net/hex/266b) (♫)
