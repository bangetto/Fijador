# Contributing Guidelines of Fijador
Thank you for investing your time in contributing to our project! Any contribution you make is appreciated, but you should follow these guidelines so the project doesn't become a mess.

### Summary
- Do not fix was already been fixed, unless that fix creates more issues.
- The fix you do should be flexiable for compatibility.
- Use the correct structure, what is provided in these guidelines.
- When opening a pull-request use one of the templates so it is easier to see what you did.


---


## 1. What to fix
In this section you'll learn what bugs to fix and the project's priorities.

#### Issues found on the bug tracker
The issues you fix should be in at least one relase, not just in snapshots. The fixes for issues that have been solved by Minecraft can be backported, but please note that you should mainly focus on what not have been fixed.

#### Issues found on this Github repository
Issues which can be found on this repository's *Issues* tab are issues that this pack creates, because this is a resource pack that focuses on fixing bugs, so if the pack intruduces an another bug it should resolved as soon as possible, even if that comes with un-fixing some fixed Minecraft bugs.


---


## 2. How to fix
### 2.1 Flexibility and compatibility
  When you fix an issue keep flexibility and compatibility in mind. This pack has to be compatible with at least the last 3 big releases (like 1.20, 1.19, 1.18) and their sub-relases (like 1.20.5, 1.19.2, 1.18.2) and with as many mods and resource packs as possible.

### 2.2 Overlay packs
  This feature intruduced in 1.20.2 asumnes the pack is updated, because it requires the listing of versions what it should be aplied to, saying just a minimum is not enough. Overlay pack should only be used if that file changed mapping and when the file doesn't load correctly on the supported versions. This also ensures easy managment of files.

### 2.3 Using the work of others
  You can use the work of others as long it doesn't break that work's license and you update the `credits.txt` file to credit the work.



---


## 3. Opening a pull-request
When your fork is ready to be merged you should not forget filling in the template in the way it request it.
