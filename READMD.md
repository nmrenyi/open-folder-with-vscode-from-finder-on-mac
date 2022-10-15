# Open Visual Studio Code From Finder On Mac


## Motivation
It's quite a common need to open VS Code from a Finder window on Mac, especially for those developers who has been customed to open VS Code from File Explorer with just a slight right click on the target folder or file.

However, VS Code on Mac does not offer this shortcut natively. So here is a **easy** and **neat** way to implement this feature.

## Methods
1. Launch *Automator*. 
2. Select *New Document* icon on the bottom of the window (highlighted with red box).
3. Select *Workflow* and click *Choose* on the windows that just comes out.
4. Find the 4th category in the *Library* list on the left side of the window. Click on it and find *Open Finder Items*. Doubt click on this term or drag it to the window on the right.
5. Choose *Visual Studio Code.app* as the application of *Open with:* from the drop down menu.
6. Press `command+s` to save the script to your favourite folder with your favourite name. Done :)

Notes:
1. *Automator* is a powerful tool natively available in macOS, which aims to design and automate user customized workflow. You can find it from `Application` folder or simple search for it with *Spotlight*.
2. *Visual Studio Code.app* may not appear in the drop down menu of step 5 as expected. You may need to choose *other* and find it. Usually the *Visual Studio Code.app* is in `Application` folder. If not, you may refer to [this post](https://code.visualstudio.com/docs/setup/mac#_installation) to move it here.
