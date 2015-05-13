#bareBonesArduino
This repo contains everything you will need to bootload and program an ATmega 328 with no external clock (only the internal 8 MHz clock). I decided to make this repo after struggling with the outdated official instructions and piecing together lots of FAQ and blogs.

This code will allow you to bootload an AVR 328P-XX using an existing Arduino in the latest [IDE Version 1.6.4](http://www.arduino.cc/en/Main/Software). There are also instructions for programming your new bootloaded AVR.

##Install
1. Go to the directory where arduino looks for sketches. You can find this by opening the IDE and going to `Preferences` and looking at `Sketchbook location`.

For example I am on a Mac and mine is `/Users/UserName/Documents/Developer/Arduino`. Open a terminal and type:
```bash
cd /path_to_Arduino_sketches/
```
Now first we need the ISP sketch that allows us to use our arduino as an external clock source. Luckily the good people at Adafruit have taken the time to write a wonderful little code to [do just this](https://github.com/adafruit/ArduinoISP.git). All you have to do is clone this repo:
```git
git clone https://github.com/adafruit/ArduinoISP.git
```

If there is a directory called `hardware` type: `cd hardware`. If not, you need to create this directory. Under mac and linux use: 
```bash
mkdir hardware
cd hardware/
```

Now we are in `/path_to_Arduino_sketches/hardware/`.

2. Clone this repo.
```git
git clone https://github.com/rlober/bareBonesArduino.git
```

3. Start up your Arduino IDE.

###Where is everything?

###What's in this repo?

###Why?

