## Google Takeout Sucks

This crap project exists because Google, in their infinite wisdom, seems to strip off photo metadata and export it as a separate JSON file with the same name as the image. 

We aim to fix that. It'll be ugly, but whatever. I'm not a real programmer, so it's fine.

### Rough Plan

We're going to begin at the top of a Google Takeout directory full of images and the aforementioned JSON files. Then, we're going to flatten and de-dupe it the whole thing. Next, we'll match up images with JSON files, update the date—I don't care about anything else—and move the file to a new directory that I can shove into Apple Photos.

I hate that this is necessary.
