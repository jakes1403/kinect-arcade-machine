# McNeese ACM Kinect Arcade Machine Project
This is a repo containing the documentation and source code for the McNeese ACM Kinect Arcade machine project.

## Quick Links to sub-projects
 * [Godot Kinect Module](https://github.com/jakes1403/gkinect)

## Project info
The intended outcome of this project is to have:
 * A custom-created game, made with the open source Godot Engine, that is fun to play, looks graphically appealing, and draws an audience.
 * A custom module for the Godot game engine to support the Kinect, and potentially add general computer vision capabilities to the open source engine.
 * An arcade machine cabinet, to house the machine hardware and make the game look appealing to potential players.

## Getting Started
Want to help? Because of the complexity of this project, you may need to read up on the tools we are using to create it.

Here are some helpful links:
 * [Creating a basic game with the Godot Engine](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html)
 * [GDScript Basics](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
 * [How to use the Kinect V2 API](https://ed.ilogues.com/Tutorials/kinect2/kinect0.html)
 * [Creating Engine Modules for Godot](https://docs.godotengine.org/en/stable/development/cpp/custom_modules_in_cpp.html)

## Current progress
Here is a picture of the latest milestone:

<img src="https://raw.githubusercontent.com/jakes1403/mcneese-acm-kinect-arcade/main/teapot.jpg" width="300" height="400">

Body Tracking is fully functional, and limb positions are taken from the Kinect and sent straight to the Godot Engine.

Already, we have created a module to support the Kinect for the Godot Engine, and you can find its Github page [here](https://github.com/jakes1403/gkinect).
