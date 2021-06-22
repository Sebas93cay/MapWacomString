# Map Wacom tablet to one screen



This script maps an installed wacom tablet to one of the detected screens available. 

## How to use

Run command.

```
./mapWacomScreen
```

When the program ask for which screen to use, select one of the screens available with the keyboard



## Example:

```
./mapWacomScreen

##################################################
These are the devices to set to the selected screen
Wacom Intuos S Pad pad                  id: 15  type: PAD       
Wacom Intuos S Pen stylus               id: 16  type: STYLUS    
Wacom Intuos S Pen eraser               id: 22  type: ERASER    
Wacom Intuos S Pen cursor               id: 23  type: CURSOR    

##################################################
Screens Available:
 0: +*eDP-1 1920/344x1080/194+0+0  eDP-1
 1: +HDMI-1 1920/408x1080/255+1920+108  HDMI-1

##################################################
Which screen do you want to map for the wacom tablet?

2
Wacom table was maped to HDMI-1 screen
```

