# hmm

## commands

for downloading a video with spanish auto subtitles in .mp4

```bash
yt-dlp --write-auto-subs --sub-langs "es" -f 22 "https://www.youtube.com/REPLACE" -o out.mp4
```

for searching for a word. the default of videogrep is searching by sentence, so with --search-type "fragment" you can ditch the sentence and only keep the word.

```bash
videogrep --input test.mp4 --search "PALABRA" --search-type "fragment" --output out.mp4
```
