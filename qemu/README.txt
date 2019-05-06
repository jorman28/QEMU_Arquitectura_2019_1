Double clicking or running the file run.bat will start a Raspberry Pi emulation using QEMU.

This only works on computers running Windows.


On running for the first time you will see a configuration screen  
The arrow keys take you up and down the list, enter or return selects an item to change
Tab (above Caps Lock key) gets you down to the two options at the bottom so you can finish.


After a few minutes you will see a black screen with the words

"raspberrypi login:"

at the bottom of the screen. Type "pi" and hit enter.

You will be prompted for a password, type "raspberry" and hit enter.



You are now on the Raspbian command line.

If you wish to set a root password, type

"sudo passwd root"

you will have to type in the root password of your choice twice.



From here you can continue to use the command line, but if you would prefer to use a window based desktop,

type "startx"

