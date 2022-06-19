# ASCII-Art-Generator

## Requirements :
    Python3, OpenCV

## How it works :
    Every video is composed by a set of frames that are played at a certain frame rate.
    
![Video Frames](./images/frames.png)

#### Since a terminal has a specific number of rows and columns, we have to resize our video to adjust to the terminal size limitations. To reach a correct     visualization of an entire frame we need to adjust the frame height to match the terminal rows, avoiding using more characters than the number of terminal columns.

![Resizing](./images/imgPixelSection.png)
