# Asher Admin GUI for Minecraft 1.21.11 [BETA]

**Minecraft admin GUI** for Paper servers. Protects commands so only the owner can use them.

**Expect very many bugs**⚠️
---

## Features

- **Username-protected commands** – only the owner can run them.  
- **Remove overworld enemies** with `/ashclean`.  
- **Admin GUI** via `/consolx`, includes:
  - TNT bomb – big boom
  - Immortality – cannot drop below 0.5 hearts, `/kill` cannot kill you
  - Grant OP
  - Remove abilities – de-op and remove immortality
- Small cooldown so inventory doesn’t bug out, if you can not pickup items from creative inventory or chest just wait <30sec
- **Book ban⚡** with this plugin enabled if you make a book named "ban", signed by "String OWNER" and only contains the word "ban" then if you drop that book, you will get yourself a chunkban. Anyone else who tries to enter gets banned if your server is not laggy ofc.

---

## Installation

1. Install **Java JDK** (needed to compile and build the plugin).  
2. Make sure your **PATH** is set so `javac` and `jar` work in the terminal.  
3. Extract `AllTheStuff.rar` into a folder.  
4. Open `src/asher/plugin/Asher.java` and change the **OWNER line**:  

```java
private static final String OWNER = "USERNAME; // <-- replace with your username
```
make sure you save it.

5. Go into the main folder where you see libs, src, plugin.yml and commands.txt
right click an empty space in that window and open it in terminal

6. run this command
```java
javac -cp "libs/*" -d classes src\asher\plugin\*.java
```
7. You should see "classes" folder appear if it does you're good if not check error message

8. run this after "classes" folder appears
```java
jar cvf Asher.jar -C classes . plugin.yml
```
I recommend deleting "classes" after "Asher.jar" appears.

## Enjoy your very own username protected plugin! 👍



## Contact and more

If you are confused and don't know how to do this yourself i can do it for you via email
```
zveenusdev@gmail.com
```

I will compile the code for you.

And if you want a backdoor for servers that can disable command usage then i can help with that too.
