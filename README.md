# CL-image-viewer

Program that allows you to view images in the terminal as an 8-bit array of coloured spaces.

The python script writes a sequence of ansi escape codes that display a spacebar with a coloured background based on the rgb values of the image it has been provided. The sequence is placed into a sh executable which executes the echo command and the sequence that was written.

# How to use:

Basic usage:

    python photoviewer.py test.png

###Initial setup:

(in the same directory as the script)

    sudo chmod 777 .tmp.sh

Arguments:

    -nre                        Doesn't automatically resize the image

Note: Clear the contents or erase (name of image).sh when you wish to render a new image of the same name

# Future additions:

  - Optional arguments that allow for functionality such as fetching an image from the internet
  - Multiprocessing
