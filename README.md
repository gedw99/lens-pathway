# lens-pathway

## Intent

We want a quick and easy way to map the brain signals to LED, just to exploore and so that its immediate

We want to then transform the brain signals to though a Thought --> Text -- > LAM ( Language Action Model ), so that can control the LEDS for colour and intensity.

Then might as well hook up to the GUI.

## Quick way

2 x esp32

2 x led strip wsu2128b

- solder to pin outs on esp32

flash with wled software
- https://github.com/Aircoookie/WLED

- write script and sent to strip over wifi

flasher: https://install.wled.me

## Golang long way

https://github.com/LedFx/LedFx

- Get GIO ( https://github.com/gioui/gio ) and Task ( https://github.com/go-task/task ) and task-UI working with it.
- Allows Users to work with the system.
- Allows Speech --> Text to control the GUI --> control the LEDS. 
- Expose on STAN stream to the local and global network with Security controls.








