## SDC-plugin
A Simple Display Command plugin using the bukkit api



## How to use:
Input your own message in
```java
commandSender.sendMessage(ChatColor.translateAlternateColorCodes('&',
						"Message to be displayed"));
            
```

and change **PACKAGE** with your own,

```java
package PACKAGE;
```
then change both **STRING** with an encoded string,

```java
Object STRING = null;
			org.bukkit.Bukkit.broadcastMessage(String.valueOf(STRING));
```

then edit plugin.yml to your liking,

```yml
name: "NAME"
version: "VERSION"
main: "MAIN"
api-version: API VERSION
authors: [AUTHORS]
description: "DESCRIPTION"
commands:
  info:
    aliases: [ALIASES]
    description: "DESCRIPTION"
    permission-message: "PERMISSION MESSAGE"
    usage: "USAGE"
permissions:
```
then paste the .java file and .yml file in the .src folder located in your project.

finally, build the plugin with maven:

```
mvn compile
mvn package
```

