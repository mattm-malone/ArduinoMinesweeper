# ArduinoMinesweeper
Simple Minesweeper clone written in Javascript for the Arduino ESP8266. 
Uses a neopixel LED matrix to represent the game board. Sends pixel data via hex values sent by simple get requests.

White = unrevealed
Green = 1 mine adjacent to square
Yellow = 2 Mines
Orange = 3 Mines
Purple = 4+ Mines
Unlit = revealed square
Red = mine, you lose!

Controls are on the html page
