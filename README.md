# Web radio to audio jack converter
A really simple internet radio/webradio to audio jack converter based on ESP32

## The Idea
The idea is to build a really easy webradio. The webradio to audio jack converter is just a box with a push button to switch channels. As I only need three predefined channels I integrated a channel indicator LEDs for each web radio channel.

This is where the initial idea is from: https://circuitdigest.com/microcontroller-projects/esp32-based-internet-radio-using-max98357a-i2s-amplifier-board. This little project just adds a little suggar around.

## Why
I just wanted to keep my old kitchen radio even if my favourite radio stations are no longer available (they moved to DAB+). So I decided to use the audio jack of my radio to listen to them.

## What we need
* ESP32 (I had a wroom from azdelivery)
* MAX98357A - an amplifier breakout board to drive a speaker or attach it to a audio jack plug
* 2 RGB LEDs
* 3 normal LEDs
* Step down converter to 5v DC

## The Schematic
![Schematic_Webradio2jackplug](https://user-images.githubusercontent.com/5586873/148019516-501ed688-36f6-4ff0-8f84-8ea78281d7af.png)
