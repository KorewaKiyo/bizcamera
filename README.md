# BizCamera 
## A business card sized camera

### Why?
I thought it was a cool and silly enough idea to be unique, and I couldn't find anyone else doing it. So I took it on myself to make it happen.

### How?
Initially I wanted to go with something STM32, as the camera module wants 1.8V, and there were some good STM32 MCUs with 1.8v, but it seemed like none of them were fast enough or had enough RAM to grab frames from the sensor. 
So I'm using the RP2350 which with PIO should have enough IO speed to just steal a frame off the data bus.

The chip itself doesn't have enough ram to store an image above 320x240 so I've added some RAM, a flash chip for code, and an SD card slot for storing images.

### What's the output like?
Yet to be seen :>

### What does the board look like?
![top](<github_username>.github.io/<repo_name>/top.png)
![bottom](<github_username>.github.io/<repo_name>/bottom.png)
rendered with [kicad-render](https://github.com/linalinn/kicad-render)


