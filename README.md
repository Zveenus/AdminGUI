1. Install Java JDK (needed to compile and build the plugin).

2. Make sure your PATH is set correctly so javac and jar work in the terminal.

3. Extract AllTheStuff.rar into a folder.

4. Go to src/asher/plugin/Asher.java and change "MINECRAFTUSERNAME" with your username. Example:
if (!admin.getName().equalsIgnoreCase("SigmaGamer67")) {

CASE SENSITIVE!!!!!!⚠️⚠️⚠️

5. Go to the main folder (where you see libs, src, plugin.yml), right click, and open a terminal there.


6. run javac -cp "libs/*" -d classes src\asher\plugin\*.java

7. A folder called classes should appear.

8. run jar cvf Asher.jar -C classes . plugin.yml

There you go!
your own admin gui.

FEATURES:
Protected with your username so only you can run the commands
Lets you remove normal overworld enemies with /AshClean
A admin gui /consolx includes
tnt bomb - big boom
immortality - cannot go past 0.5 hearts
grant op - yk
remove abilites - deop and un-immortalizes


ENJOY!
