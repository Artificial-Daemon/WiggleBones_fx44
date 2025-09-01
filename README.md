# WiggleBones_fx44
Small unofficial community update for Wiggle 2 blender addon to make it compatible with Blender 4.4.

I am not the original creator of this addon, all credit goes to shteeve3d. See the original at https://github.com/shteeve3d/blender-wiggle-2.


I am using Blender 4.4 and wanted the functionality of this addon, but encountered some issues when trying to use it. 
The issues I encountered:
* If a collision object was selected it would cause that bone to grow exponentially, regardless of contact with the object or settings selected
* Only collision object selection modes were either an individual object or an entire collection

I really wanted to use this addon, so I made some slight modifications and tweaks.
The collision system now works again, however complex meshes can cause issues with the bones trying to glitch through.
* This can be fixed with some tweaking of settings or using empty objects for collision simulation.
* If you encounter issues during the animation process, I have found using simple collision objects to be very helpful

There is also a new collision object selection mode called "Objects". With this you can choose multiple object for collision with bones. 
I have found this to be far more performant than using an entire collection, and allows far greater control of how your armature reacts.

My updates were done as a way to make the existing addon useable. I have achieved good results with it so far, but I cannot guarantee your experience will be the same.
This is absolutely not an official update to the program, and may or may not be supported in the future. 

This was done for fun and to make the tool available for Blender 4.4, and I thought I would share my results in the event somebody else was in a similar situation.

For information on how to use the addon, please visit the original github page https://github.com/shteeve3d/blender-wiggle-2.
