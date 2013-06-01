# ImageSonifyer

Version: 	   0.2  
Created date:  2013-01-07  
Modified date: 2013-04-18

## Features

This program will sonify images by reading through the image from left to right, and carry out an inverse FFT on the data. This means that information in the lower part of the image will be in the lower frequency register, and vice versa. Any type of image will work, but the program was originally developed for sonifying motiongrams. Motiongrams are spatiotemporal representation of motion, created from video recordings.

## Usage 

Open patch, select camera, click-drag to crop image, press escape to go fullscreen. 

## Credits

Inspiration to the Max implementation come from [Barry Moon](http://www.barrymoon.com/) through his [video tutorial](http://www.youtube.com/watch?v=rnERzPwRa4g&lr=1) on creating something similar to [Metasynth](http://www.uisoftware.com/MetaSynth/).

## Author 

Alexander Refsum Jensenius  --- http://www.arj.no  
University of Oslo, Department of Musicology, fourMs lab

## Requirements

- [Max](cycling74.com/products/maxmspjitter/) from Cycling '74

## License 

Released under the GPL license
http://www.gnu.org/copyleft/gpl.html

## History 

v0.1: First working version