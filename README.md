![](https://amend.mrtron.dev/images/amendfullcolor.png)

# Amend
A plugin that auto updates purpur to the newest version based on the Minecraft version.
 ## HOT-SWAPPING JARS IS NOT THE BEST IDEA, PLEASE USE AT YOUR OWN RISK. 
 *(there have been no problems though so far based on different types of sized worlds and what else I have tested. Still, be careful anyways :D)*
 
# Download

Currently as of now you can download it on our new website @ [amend.mrtron.dev/download](https://amend.mrtron.dev/download)
 
 # How to make it work
 Currently **IT ONLY UPDATES PURPUR, NOT ANYTHING ELSE**.
 It grabs the latest version from Purpur's API and just replaces the server jar.
 
 If you would like to use it there are a few things you need to do. 
 - First make sure purpur is installed and name the jar to whatever you'd like. Please make sure to change it in the config though, so the system can find your jar file.
 ```yml
#
#    ╭━━━╮╱╱╱╱╱╱╱╱╱╱╭╮
#    ┃╭━╮┃╱╱╱╱╱╱╱╱╱╱┃┃
#    ┃┃╱┃┣╮╭┳━━┳━╮╭━╯┃
#    ┃╰━╯┃╰╯┃┃━┫╭╮┫╭╮┃
#    ┃╭━╮┃┃┃┃┃━┫┃┃┃╰╯┃
#    ╰╯╱╰┻┻┻┻━━┻╯╰┻━━╯

# This changes the jar file name. PLEASE MAKE SURE IT MATCHES THE JAR FILE NAME OR ELSE IT WILL CREATE A NEW JAR FILE.
# If you forget you are using a different server type instead of Purpur and the plugin is running, it will automatically override it to purpur.
jar-name: {PUT THE JAR FILE NAME HERE WITH THE .JAR}


# Config Version. Like every spigot dev, we ask that you DO NOT CHANGE THIS PLEASE.
config-version: 7
```
 - Then place the (plugin) jar in and it will automatically update it to the newest version, ***please note as of now the plugin is updating the latest `1.19.1` builds and will continue to update until a new release comes out, then you will need to come back here to get the newest plugin update.***
 
 Update checks for the plugin are currently unavailable to switch off, but we only create the update notification if its a critical update, not a fancy one.
