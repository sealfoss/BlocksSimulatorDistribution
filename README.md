# BlocksSimulatorDistribution
Distribution Repo for Blocks Simulator

Move around with the left joy stick.
Turn with the right joy stick.
Jump by pressing the left joy stick like a button.
Press and hold the grip button to grab a block.
You may snap blocks to the floor pieces, or to each other by holding one in each hand.
To detach a block, grab the block and pull the trigger.

Exit with the big red button.
If selected with the switch next to the button, a .obj will be exported to /sdcard/ on the quest.
Due to a bug with the Quest (per John Carmack on Twitter), you may not be able to see exported
files in your files explorer. If this happens, you'll need to use adb from a command line in 
order to access the files. Commands are as follows:

To view the files in /sdcard/: 

adb ls /sdcard/

To pull a file from the device to your computer:

adb pull /sdcard/<filename.obj>

You can also use the adb shell to access these files, but I don't recommend it for the 
uninitiated. 
