# Pascal-VOC-to-COCO-json

This code is mostly taken from https://github.com/Tony607/voc2coco
with some modifications for my setup. Specifically, it allows non-integer named files, but still assumes the files are unique. Secondly it uses a reference to the image folders to determine the image's path rather than assuming the path in the XML annotations is still correct. This allows me to shift my images around as I need without redrawing bounding boxes.

Requirements:
  Image file names must be unique.
