This is one of my first major electronics projects (post-CanSat)!

## Project

The goal of this project is to design a custom smartwatch that fits for my personal use case. That includes:

- Shows the time (obviously)
- Maintains a BLE connection with the associated phone
    - Displays notifications
    - Displays current song playing on Spotify
- Has a push-to-talk mic
    - Streams voice notes to the associated phone, for possible analysis later

## Organization

`mc-screen-breakout` has the first revision of the smartwatch PCB, including the MCU module (containing RF stuff asw), a USB-C port, exposed SWD pins, the screen FPC connector, and the microphone.

`watch` **will** contain iterations of the watch PCB that connect to battery and (theoretically) function properly inside the full system, rather than a breakout.
