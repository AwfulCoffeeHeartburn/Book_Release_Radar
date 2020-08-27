# Priority Button
So far I've added features that include:
The user can prioritize items on their to-do list.
The indexes of the selections are saved to a text file
The contents of the text file are loaded to a list automatically at program startup
The items are the list are fed to the GUI where they resume their priority status

These features are necessary because when the program is closed the background colors, or "priority status" designated by the user is not saved and there are no priorities when the program restarts.

I still need to:
Configure a feature that removes priority indexes from the list and textfile that contain priorities when the user desires this.
Fix the bug that is causing the program to crash when it attempts to load with an empty priority index, or "colors" file.
