# Video animation on scroll demo

## Generate image frames from video file using ffmpeg

```sh
ffmpeg -i inputfilepath.mp4 -r 2 frame_%04d.png
```

`-r 2` forces the output framerate to be 2, and the output file is a png.
