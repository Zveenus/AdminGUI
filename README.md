# Asher Admin GUI for Minecraft 1.21.11

A full-featured **Minecraft admin GUI** for Paper servers. Protects commands so only the owner can use them.

---

## Features

- **Username-protected commands** – only the owner can run them.  
- **Remove overworld enemies** with `/ashclean`.  
- **Admin GUI** via `/consolx`, includes:
  - TNT bomb – big boom
  - Immortality – cannot drop below 0.5 hearts, `/kill` cannot kill
  - Grant OP
  - Remove abilities – de-op and remove immortality
- Small cooldown (30s) so inventory doesn’t bug out.  

---

## Installation

1. Install **Java JDK** (needed to compile and build the plugin).  
2. Make sure your **PATH** is set so `javac` and `jar` work in the terminal.  
3. Extract `AllTheStuff.rar` into a folder.  
4. Open `src/asher/plugin/Asher.java` and change the **OWNER line**:  

```java
private static final String OWNER = "Zveenus"; // <-- replace with your username
