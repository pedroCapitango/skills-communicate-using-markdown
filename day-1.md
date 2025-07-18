# Daily Leaning
## Morning Planning
- [ ] Go to School
- [ ] Learn About [Github Pages]
- [ ] Improve everday
## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
