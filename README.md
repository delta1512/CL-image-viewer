# CL-image-viewer

Program that allows you to view images in the terminal as an 8-bit array of coloured spaces.

The python script writes a sequence of ansi escape codes that display a spacebar with a coloured background based on the rgb values of the image it has been provided. The sequence is placed into a sh executable which executes the echo command and the sequence that was written.

# How to use:

1. Place an image that is called 'test.png' in the same directory as 'photoviewer.py'
2. Run 'photoviewer.py'
3. Run in bash (unless you already have permission): sudo chmod 777 test.sh
4. Run in bash: ./test.sh
Note: Clear the contents or erase 'test.sh' when you wish to display a new image

# Future additions:

  - Automatic resizing of images
  - Removal of the sh executable feature making the script standalone
  - Optional arguments that allow for functionality such as fetching an image from the internet
 
  - (For personal education) Implementation of a linked list for search efficiency