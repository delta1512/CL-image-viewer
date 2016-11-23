# CL-image-viewer

Program that allows you to view images in the terminal as an 8-bit array of coloured spaces.

The python script writes a sequence of ansi escape codes that display a spacebar with a coloured background based on the rgb values of the image it has been provided. The sequence is placed into a sh executable which executes the echo command and the sequence that was written.

# How to use:

{required} [optional]

1. python {name and directory of image} [-o name of output file]
3. Run in bash (unless you already have permission): sudo chmod 777 (name of image).sh
4. Run in bash: ./(name of image).sh

Note: Clear the contents or erase (name of image).sh when you wish to render a new image of the same name

# Future additions:

  - Automatic resizing of images
  - Removal of the sh executable feature making the script standalone
  - Optional arguments that allow for functionality such as fetching an image from the internet
  - Multiprocessing
