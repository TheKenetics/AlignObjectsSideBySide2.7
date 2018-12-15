# AlignObjectsSideBySide
Blender addon for aligning objects side by side along an axis by their bounding boxes

## Why
Couldn't find an easy way to line up objects side by side, so I made this.

## Installation  
### Requirements  
Works on Windows, Mac, and Linux.  
Meant for Blender 2.79b, but may work on previous versions too.  
### How to Install  
Download the python file (put it in a place where you can easily find it, like your desktop)  
In Blender's settings, go to the addons tab  
At the bottom, click "Install from File"  
Find where you put the python file, select it, and click "Install from File"  

## Using
Warning: This addon will change the origins of the objects to be at the center of their bounding boxes.
1. Place objects in order along the axis you want to line them up on. (Optional)
2. Select all the objects you want to align.
3. Use Operator Search (Spacebar) to search for "Align Objects Side by Side" and run it
4. Change the axis and padding in the tools sidebar or the the Last Run Operator dialog (F6) (Optional)

### Notes:  
This addon will change the origins of the objects to be at the center of their bounding boxes.  
