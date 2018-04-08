Modularity
==========

 

As said before, this part of Java 9 really deserves a workshop of its own. We
can only give you tiniest taste of it.

 

This small exercise will give you a very small taste of it, and furthermore
demonstrates the new jlink.

 

In the src folder you'll find an empty `module-info.java`. You'll need to enter
code there so the program compiles.

 

There are 5 shell scripts provided that help you run through the whole
development cycle:

1.  `compile.sh`: compiles the source code.

2.  `run.sh`: runs the application.

3.  `package.sh`: packages the application into a modularized JAR.

4.  `deps.sh`: uses jdeps to do a dependency analysis on the JAR.

5.  `link.sh`: creates a custom, minimal JRE, containing the JAR as well.

 

A tutorial that goes more in-depth can be read here:
https://blog.codefx.org/java/java-module-system-tutorial/.

 

If you prefer watching a vid, we’ve got you covered as well: here’s the 'Java 9
Modularity in Action' video session by Sander Mak & Paul Bakker:
https://youtu.be/OEKcuywm0mk. These guys are the authors of the book mentioned
earlier.

 

As for Java 9 Modularity not having version control, we've found an interesting
discussion here: https://blog.codefx.org/java/dev/will-there-be-module-hell/.

 

 
