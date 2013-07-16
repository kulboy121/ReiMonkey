## ReiMonkey

**Latest recommended release: [ReiMonkey 2.0.2](https://github.com/TekkifyLife/ReiMonkey/releases/download/2.0.2/ReiMonkey.2.0.2.jar)** for Minecraft 1.6.2

* ~~[Forum topic](http://www.minecraftforum.net/topic/1397908-162-reimonkey/) at Minecraft Forums~~ **Forum topic deleted by Minecraft Forum staff**
* [Original mod](http://minecraftmonkey.wordpress.com/2012/04/24/reimonkey/) at minecraftmonkey

ReiMonkey currently requires ModLoader for 1.6.2, Minecraft Forge 9.10.0.789+, or Forge Mod Loader v6.2.19.789+. ReiMonkey is 
a stand-alone mod and does not require Rei's Minimap to use, although it will not function in any useful way.

### Old Versions

Minecraft 1.5.1 + 1.5.2 by woop [[Download](http://www.mediafire.com/?m3j6g2vmvts7518)]  
Minecraft 1.4.6 + 1.4.7 by IX iTzRogue XI [[Download](https://dl.dropbox.com/u/23755556/ReiMonkey/Downloads/1.4.6/ReiMonkey%20v1.1.zip)]  
Minecraft 1.4.5 v1.1 by IX iTzRogue XI [[Download](http://goo.gl/I1YHg)]  
Minecraft 1.4.5 v1 by IX iTzRogue XI [[Download](https://dl.dropbox.com/u/23755556/ReiMonkey/mod_ReiMonkey.class) unavailable - 404]  
Minecraft 1.4.2 by catmenFromTV [[Download](https://dl.dropbox.com/u/36690916/ReiMonkey%5B1.4.2%5D.zip)]  
Minecraft 1.3.2 by catmenFromTV [[Download](https://dl.dropbox.com/u/36690916/mod_ReiMonkey%5B1.3.2%5D.zip)]  
Minecraft 1.3.1 by Crunchy_Nut [[Download](https://dl.dropbox.com/u/44164076/MinecraftMods/mod_ReiMonkey.zip) unavailable - 404]  
Minecraft 1.2.5 by Crunchy_Nut [[Download](https://dl.dropbox.com/u/44164076/MinecraftMods/mod_ReiMonkey.zip) unavailable - 404]  
Minecraft 1.2.5 by the original author [[Link](http://minecraftmonkey.wordpress.com/2012/04/24/reimonkey/)]

### Reporting issues

* Only report an issue if there is an issue with the mod not a question.
* If possible, include a crash report if there is a crash.
* Please make sure to check if the issue has not been reported before.


### Contributing
Fork this repository and make changes, then submit a pull request and I will review the changes. If you would like
to access this repository directly, send a message to my [e-mail](mailto:tekkifylife@outlook.com) or private message
[me](http://www.minecraftforum.net/user/2156440-tekkifylife/) or
[JonaK](http://www.minecraftforum.net/user/1512157-jonak/) on the Minecraft Forums.

### Building From Source
1. Download [MCP 8.04](http://mcp.ocean-labs.de/index.php/MCP_Releases) and [ModLoader 1.6.2](http://www.minecraftforum.net/topic/75440-v162-risugamis-mods-updated/)
and set MCP up anywhere. Instructions are [here](http://mcp.ocean-labs.de/index.php/Making_ModLoader_mods_with_MCP#Setting_up_MCP)
from the official MCP website.
2. Download and install [Apache Ant](http://ant.apache.org/). Make sure Apache Ant is working before attempting to build.
3. Download ReiMonkey's [source code](https://github.com/TekkifyLife/ReiMonkey/archive/master.zip) and unzip it to anywhere.
4. In the source directory's root, most likely `./ReiMonkey`, create a new file named `build.properties`.
5. Type the following information into `build.properties` and save the file:  
<pre><code>dir.mcp={MCP directory path}
dir.reimonkey={ReiMonkey source directory path}
dir.release={directory where the built source shall be dumped}
minecraft.version=1.6.2
reimonkey.version=2.0.3_dev</code></pre>
6. Open Command Prompt in Windows or Terminal in OS X and Linux and change the directory to the source directory.  
i.e. `cd (source directory path)`
7. Run Apache Ant by typing `ant` and the mod should build to the directory specified in `build.properties`.
