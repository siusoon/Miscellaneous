Convert all png files within a directory to an animated gif 

1. Install ImageMagick on Mac OS ver 10.14.x 
```
brew install imagemagick
```

2. Depends on Ghostscript fonts
```
brew install ghostscript
```

3. If errors occur including the link issue, try `brew doctor` then just follow the terminal's suggestion

4. The actual command line to combine all images into one single animated gif (go to the directory with the png files)

`magick -delay 16 -loop 0 *.png output.gif`

## Reference:
https://imagemagick.org/Usage/anim_basics/
