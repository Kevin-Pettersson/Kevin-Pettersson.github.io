---
title: "The Ultimate Breadboard Power Supply"
permalink: "/breadboard/"
layout: page
---

If you have ever been in the market for something to power all your projects but prefer to use something small and portable then look no further. My power supply can supply voltages from 3.3 V all the way up to 25 V therby eliminating the need for a big, chunky and expensive power supplie, my solution runs on USB-C and only requires 5 V 1 A input. The power supply is as small as the cheap chinese ones which can only handle 3.3 V or 5 V poorly. 


Technial Specification:
* USB-C, can be powered via computer or phone charger etc 
* Short circuit, over current, over temperature and in-rush protection
* Soft start
* Programmable voltage indicator 
* Small size 

## Usage
To use the power supply simply push it into the breadboard and connect a usb c power source thats it. The voltage adjustments have been split into two seperate functions, the right hand power rail will supply either 3.3 V or 5 V (selected via the switch (labeled 3,3/5V) in the right top corner) and to adjust the left hand sides voltage, simply turn the potentiometer (labeled VOLTAGE_ADJ) and the voltage will be displayed by the 5 LEDs located at bottom of the PCB. 


## Reprogramming the voltage indicator

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```



