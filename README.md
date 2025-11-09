# Pebble Horizon
## Overview
This simple Pebble watch application is a demonstration "toy" displaying an artificial horizon (attitude indicator) based on accelerometer data. It shows a horizontal line rotated according to the tilt of the watch and includes several graphical elements resembling an aircraft instrument in Cesna-like design.

**Note:** This application is not intended for real use during flight or for precise attitude measurement. It is solely for experimental and demonstration purposes on the Pebble platform.

## How the Application Works
- It samples accelerometer values and calculates the horizon rotation angle based on the X-axis.
- Uses trigonometry to draw the rotated horizon boundary, segments, and indicators.
- Turns on the display backlight when the app activates for better visibility.

## How to use
App is not at Pebble store for now, so you need to compile and load the app onto a Pebble device or emulator. Upon launch, the app renders a basic artificial horizon reacting to watch tilt.

## Contributing and use of code
Code is [Unlicense](https://unlicense.org/), you can use it freely in any manner. Also any contribution is realy welcome ;)
