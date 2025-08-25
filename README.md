# sonshi-helper
A shell script you can run when starting xinput to disable laptop keyboard when you have an external keyboard plugged, useful for sonshi style.

First argument is for the keyboard you want to disable when the external one is detected, the second argument is for the external one.
To figure out the names of your keyboard, run xinput in a terminal and then run it with the names of your keyboards.

For me it would be something like this
```./sonshi-helper 'AT keyboard' 'Topre Corporation HHKB Professional'```
