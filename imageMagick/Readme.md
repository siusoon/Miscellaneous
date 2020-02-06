Convert a directory with all png files to an animated gif 

1. Install ImageMagick on Mac OS ver 10.14.x 
```
brew install imagemagick
```

2. Depends on Ghostscript fonts
```
brew install ghostscript
```

3. If errors occur including the link issue, try `brew doctor` then just follow the terminal's suggestion

4. Actual command line to change the image (go to the directory with the png files)

`magick -delay 200 -loop 0 *.png output.gif`
