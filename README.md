This project has been stripped of all references to the Bukkit
==============================================================
API project as it can be found on https://github.com/Bukkit/Bukkit
==============================================================

All org.bukkit.CLASSNAME_HERE references in the code of this
program references to the wolf in a Bukkit code found on 
https://github.com/Wolf-in-a-bukkit/Wolf-in-a-bukkit

This package is present to aid in the reverse enginering of API
functionality so craft bukkit can function WITHOUT the bukkit api
and WITH the wolf in a bukkit api whilst maintaing compatiblity!

This project as it stands in this repository is fully LGPLv3
compliant!

WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING 
*****************************************************************
THIS CRAFTBUKKIT MAY NOT BE DISTRIBUTED UNDER ANY CIRCUMSTANCES
TOGETHER WITH A COPY OF THE BUKKIT API WETHER IT BE COMPILED OR
SOURCE CODE!
*****************************************************************
WARNING WARNING WARNING WARNING WARNING WARNING WARNING WARNING 




LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL *****************************************************************

The following terms are applicable in this document:

Wolf in a Bukkit: a NEW API X11/MIT licensed implementation to
work with Craftbukkit, reverse enginered from craftbukkit functionality and bug report found at 
https://github.com/Wolf-in-a-bukkit/Wolf-in-a-bukkit

Bukkit API: The GPLv3 of Bukkit found at 
https://github.com/Bukkit/Bukkit

Craftbukkit: The LGPL implementation that used the Bukkit API in
the past and will now be modified to use the wolf in a bukkit api.

GPLv3: The GNU Public License version 3

LGPLv3 : The Lesser GNU Public License version 3

X11/MIT : The X11 license, commenly referred to as MIT.

This is the source code of Craftbukkit's Minecraft server jar. This
source code of the server jar, or compiled version of it 
may not be distributed with any GPLv3 Software because it is
fully incompatible!
It is incompatible through its own license(LGPLv3) and through
the proprietary software fully owned by Mojang AB.

The Minecraft server code is used in this software package is
used without official permission of Mojang AB but Mojang AB has a
history of not enforcing their rights concerning modding via
Craftbukkit, even encouraging modding (see the EULA). 
The moment they start enforcing their rights this project will be
deleted.

You cannot and may not use any immediate libraries to link
this to the Bukkit API and then distribute the package.
This is because the immediate will become GPLv3 as well by the
action of linking against the GPLv3 library.
In short, GPL sucks. Thanks grum for choosing that 4 years ago.

This Craftbukkit will hold all its references to org.bukkit in
the code but will not compile in this package as it stands now.

The Wolf in a Bukkit code is being reverse enginered from
Craftbukkit code, plugin code and bug reports. The Wolf in a
Bukkit API will gain a spot in the org.bukkit package with links
to the original hooks deduced from previously mentioned methods to
maintain compatibility with plugins that were created with
the Bukkit API since those will look for a package org.bukkit.*
files.

These files however will be unrelated to the original Bukkit API
and will be reverse enginered and the reverse enginering
documented in the code by means of comments. This sucks but is
the only legal way to accomplish this. Prepare for source code
with HEAPS of comments where we deduced functionality from.

In short:
THIS CRAFTBUKKIT IS NOT INTENDED FOR USE WITH THE GPLv3 BUKKIT API!
THIS CRAFTBUKKIT IS INTENDED FOR USE WITH THE X11/MIT LICENSED WOLF IN A BUKKIT API!

LOOPHOLE!

GPLv3 provides a loophole to private end users and companies. Please pay close attention: You may, in the privacy of your own
household or company modify the software as much as you want,
even in ways that would violate the GPLv3 License. BUT, YOU ARE
NOT ALLOWED TO DISTRIBUTE THAT SOFTWARE, unless
you can do this under full GPLv3 means. Which would entail you
getting permission from Mojang AB to distribute their source code
under GPLv3. Good luck with that!

Be WARNED though that compatibility with a Bukkit API software
package cannot be guaranteed since this Craftbukkit is intended
for use with the wolf in a bukkit API.

Steps you would have to take to make this happen:

Download Craftbukkit. Download Bukkit.
Place the files from bukkit in the src/main/java/org/bukkit
directory in the corresponding directory of Craftbukkit.
Use Maven to compile with the command: mvn clean install

You will then have your own personal copy of Craftbukkit with the
Bukkit API. AGAIN: YOU ARE NOT ALLOWED TO DISTRUBTE THAT COPY!
The file will be in the directory called target.

******************************************************************
LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL LEGAL


CraftBukkit
===========

A Wolf in a Bukkit (Minecraft Server API) implementation

Bugs/Suggestions/helping out: http://reddit.com/wolf_in_a_bukkit

This Craftbukkit is stripped of what is known as the Bukkit API.
It will not compile since it misses the Bukkit API.

The Wolf in a Bukkit API will be built to make this package
compile again https://github.com/Wolf-in-a-bukkit/wolf-in-a-bukkit
Feel free to help out reverse engineer Craftbukkit :D We could
use the help!


Compilation
-----------

We use maven to do the magic and get dependencies from the Bukkit project - sans Bukkit API :(

* Install [Maven 3](http://maven.apache.org/download.html)

* Check out this repo and: `mvn clean package`
