# Half-Life 2 GamepadUI

## What is it?

Source code for the Steam Deck GamepadUI I made used by Half-Life 2, Episode 1, Episode 2 and Portal 1.

It looks like this:

![Image of Half-Life 2 main menu with GamepadUI](.assets/image.png)

It's definitely not the cleanest thing in existence, especially as it was pretty rushed for the Steam Deck launch. However, you may be able to get some use out of it.

## What is here?

Provided is the full GamepadUI code, as well as the .vpc projects to build it.

You will need to add gamepadui for each game to your projects.vgc and groups.vgc for the Visual Studio, etc projects to be generated.

Also provided is a modified cdll_client_int.cpp with the modifications needed for GamepadUI stuff to work.</br>Check out the parts that reference GamepadUI and merge them into your codebase.

## SDK 2013 Notes

SDK 2013 by default does not have the modifications to the regular GameUI that were made that do things such as hide the main menu logo, or have the new loading screens. </br>
Provided in `game/bin` is a copy of GameUI for SDK 2013 with the modifications you can use, unfortunately the code for this cannot be provided.

Special thanks to Madi for taking my code and making it compile against SDK 2013.</br>
Thanks to my friend Dan Smith for helping with getting some screenshots for the chapter art.