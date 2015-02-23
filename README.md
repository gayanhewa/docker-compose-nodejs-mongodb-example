# Simple List Application on the Raspberry Pi

This is a fork of [felixrabe/fig-nodejs-mongodb-example](https://github.com/felixrabe/fig-nodejs-mongodb-example) to test `fig` and `docker` on a Raspberry Pi.

## Preparation

1. Download the hypriot-pi SD card image as described in [blog.hypriot.com](http://blog.hypriot.com/kick-ass-raspberry-pi-2-having-a-forbidden-love-affair-with-docker-1-dot-4-1)
2. Flash the SD card image.
3. Boot the Raspberry Pi
4. Log into the Raspberry Pi with `root` and passwort `hypriot`. Docker 1.4.1 is already running, so we now have a good platform to work with.

## Installation

On the Raspberry Pi, install `fig`

```bash
apt-get install python-pip
pip install fig
```

Now clone this repo and power up the two containers with `fig up`.

```bash
git clone https://github.com/StefanScherer/fig-nodejs-mongodb-example.git
cd fig-nodejs-mongodb-example
fig up
```


License
-------

The MIT License (MIT)

Copyright (c) 2015 Stefan Scherer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
