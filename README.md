![Logo](http://i.imgur.com/mqn4TON.png)

[![MCVersion](https://img.shields.io/badge/Minecraft%20version-1.8%20%26%201.12.1-orange.svg)](https://minecraft.net)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/mit-license.html)
[![Modules](https://img.shields.io/badge/Modules-6-yellow.svg)](https://github.com/xTACTIXzZ/Hydrazine/wiki/Module-list)
[![Status](https://img.shields.io/badge/Status-Beta-red.svg)](http://i.investopedia.com/dimages/graphics/beta03.png)
[![ProgVer](https://img.shields.io/badge/Program%20version-1.0-blue.svg)](https://github.com/xTACTIXzZ/Hydrazine)



***This will be a fork ho Hydrazine!***

What is going to be new in Aerozine will be few GUI changes and some modules changes.


## Features
* Cracked and Premium Server support
* Authentication proxy support
* Client proxy support (socks only)
* Ability to load cracked usernames and account credentials from file
* Delay between client connections (throttle delay)
* Module support
  * Default modules
  * Custom / third party modules

## How to use Aerozine
[Tutorial](https://github.com/xTACTIXzZ/Hydrazine/wiki/How-to-use-Hydrazine)

## Modules
### What are modules
Modules are essential for xTACTIXzZ to work. They add all of the functionality to the program and without them, Hydrazine would not be able to do anything.

#### Built-in modules
Hydrazine has some built-in modules that you can execute right from the beginning. To see a list of available modules, start Hydrazine with the '-l' switch. If you want to run a module from that list, you have to start Hydrazine with the '-h' and '-m' switch. '-h' needs to be followed by the target hostname or ip address and '-m' needs to be followed by the module name.

*Example:* ```java -jar Aerozine.jar -h 127.0.0.1 -m info```
#### External modules
Hydrazine has the capability to execute external modules by simply running the program with the '-m' switch but this time it is followed by the absolute file path of the module.

*Example:* ```java -jar Aerozine.jar -h localhost -m /home/user/Desktop/module.jar```

### Environment variable
If you have a folder that contains some external modules, you can set up an environment variable called "**HYDRAZINE**" (has to be uppercase, without quotation marks) with the value being the file path to that folder (e.g. /home/user/modules/) in order to simplify the process of starting external modules. Now, if you'd like to start a module from that folder, you can simply type it's name instead of the full file path to start it.

*Example:*

**This:**

```java -jar Aerozine.jar -h 127.0.0.1 -m /home/user/modules/module.jar```

**Becomes this:**

```java -jar Aerozine.jar -h 127.0.0.1 -m module```

### How to write your own modules
// todo

## Credits :zzz:

* Steveice10 for his awesome library [MCProtocolLib](https://github.com/Steveice10/MCProtocolLib)
* [Apache Commons CLI](https://commons.apache.org/proper/commons-cli/)
* xTACTIXzZ for the main project <3
