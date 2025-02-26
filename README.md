# Somfy-Situo-IO-ESP32
Journal of hacking a Wemos S2 mini onto a Somfy Situo IO 1 Pure II for use with HomeAssistant.
I just want to control the 3 (or maybe all 4) buttons from Home Assistant to automate my screens.

## Findings
Checking continuity between front and backside from left bottom pin on button to other side triggered the button.
Think the bottom side will work to solder wires to.
![frontside.jpg](images/frontside.jpg)
![backside.jpg](images/backside.jpg)

### Idea for layout
Want to keep the remote as original as possible. The idea is to put the S2 mini inside the remote if it fits with a little bit of cutting.
Hopefully, I can remove the battery and use that space for the board.

The buttons still have to properly function when they're manually pressed.

![concept_layout.jpg](images/concept_layout.jpg)

## TODO
1. Remove the battery
1. Solder wiring to the contacts
1. Connect the wiring to a perf board to test functionality
1. Solder the wiring to the S2 mini
1. Cut a hole for the USB-C connector to fit a cable to
1. Get it all back together
1. Enjoy home automation