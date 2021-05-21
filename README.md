# imagesort
Quickly sort images by orientation.

I wanted to automatically sort my wallpapers by landscape and portrait orientation, after downloading a batch of them and realizing that most of them are in portrait mode, while my monitor is actually in landscape orientation. Didn't find a program, so I wrote my own, and now I use it all the time, so I figured I'd share it.

## Installation

It's a simple shell script. Just download it anywhere (preferably somewhere in your PATH) and execute it. Depends on ImageMagick.

## Usage

Just cd into your desired directory and execute the script. Alternatively you can run it from anywhere with imagesort [directory]. It will automatically create two folders called "portrait" and "landscape" , and it will move all .png, .jpg, and .gif files into those folders, based on their orientation. That's it.
