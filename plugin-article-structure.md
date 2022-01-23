# JetBrains Plugin Article Structure

This document reviews and suggests a new structure for the JetBrains plugin
section of the documentation. 

## Organization

The current structure of the JetBrains plugin section should be reorganized.

### Quick Tour
The first section should be the current Quick Tour article. Most readers will want to see
how the plugin is used, explore basic (or adavanced) featurs, as well as sample some images of 
the user interface (UI). I would also recommend here to move away from screenshots and to 
identify the parts of the plugin that are the most sought after, or have the greatest impact and
convert them to videos. Vidoes will help the users understand better what they are seeing and provide 
a more immersive "tour" of the plugin.

### Installation
The second section would be the installation instructions. Once the user has seen and experienced (through a video) the added\
value the plugin has to offer, he will then want to install it. I would change the requirements section and rewrite it as
a bulleted (check) list of prerequisites. Including:
1. Link to free registration
2. Minimum version needed and type (for example community edition, webstorm, pycharm etc. and/or stable release version number)
3. additional plugins needed (for example python, java, etc.)

I would also try and keep the instructions generic as possible. JetBrains IDEs cane be run on Windows, Mac, and Linux operating systems
and while the menus are labeled differently, the process is really the same.

### Authenticate

The third slot is the correct location for the authentication. It is at this point after you have installed
and configured the plugin you will go to use it. In my opinion, I think there should be a method for authenticating
the plugin automatically using current authentication applications and/or methodologies. I would forgo many of the
screenshots since the user will be in the user interface. Also, should you make changes to the user interface, you will 
need to find all the locations where these screenshots are taken and then replace them all. If the company policy is that
each time you restart your IDE you need to authenticate your plugin, then it is important to state that in the quick tour.
If you can create an automated process for authentication, then this section should be rewritten and added to the installation
section. Most users will enable and authenticate the plugin as soon as it is installed.

### How To Section

In this section I would group the articles for **Dynamic logs**, **Snapshots**, and **Metrics**. The lead in of a "How To"
section almost always piques a reader's interest. In addition, in the future you may have additional things you want to add to 
this section of the documentation.

## General Comments

1. I would recommend this flow for all IDE plugins. In the VSCode set, it seems you are missing the quick tour.
2. In my opinion you have covered all that is needed for the plugin there does not appear to be any redundant articles in this section.
3. Looking through some other parts of the documentation, I see there are other places where I would reorganize as well.
This includes the `java` and `jvm` agent. The **System Requirements** is on its own page and really should be part of the **Installing the JVM agent**
as part of the prerequisites.

