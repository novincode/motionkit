MotionKit Render Output
=======================

This folder contains your rendered animation as a PNG sequence.

Files:
- frame_0001.png, frame_0002.png, ... — Your animation frames
- manifest.json — Technical data (FPS, dimensions, frame count)

How to Use
----------

DAVINCI RESOLVE:
  1. Open DaVinci Resolve
  2. Go to Media Pool
  3. Drag this entire folder into the Media Pool
  4. DaVinci will detect it as an image sequence automatically
  5. Drag the sequence to your timeline

ADOBE PREMIERE:
  1. File → Import
  2. Select the first frame (frame_0001.png)
  3. Check "Image Sequence" at the bottom
  4. Click Import

AFTER EFFECTS:
  1. File → Import → File
  2. Select the first frame
  3. Check "PNG Sequence" checkbox
  4. Import

FINAL CUT PRO:
  1. File → Import → Media
  2. Select all PNG files
  3. They'll import as individual frames
  4. Select all in timeline, right-click → Create Compound Clip

BLENDER (Video Sequencer):
  1. Add → Image/Sequence
  2. Select all PNG frames
  3. Set frame rate in Properties panel

CANVA / KAPWING / ONLINE TOOLS:
  Upload frames and set duration per frame manually.
  Most tools expect ~0.04s per frame for 24fps.

Frame Rate
----------
Check manifest.json for the exact FPS used.
Make sure your editor timeline matches this FPS for correct playback speed.

Questions?
----------
https://github.com/novincode/motionkit/issues

Made with MotionKit
https://github.com/novincode/motionkit
