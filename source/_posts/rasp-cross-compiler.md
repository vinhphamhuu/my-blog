---
title: Cross Compiler to Raspberry Pi
---

The following list summarizes the main steps to cross-compile Qt 5.12 for Raspberry Pi, we will be describing each of them in this post. The [Pi] label means this action is done in the Raspberry Pi, whereas [Host] means it has to be performed in you computer.
----
# Steps
1. Install development libraries – [Pi]()
2. Prepare target folder – [Pi]
3. Create working folder and set a toolchain – [Host]
4. Create and configure a sysroot – [Host]
5. Download Qt – [Host]
6. Configure Qt for cross compilation – [Host]
7. Compile, install and deploy Qt – [Host]
8. Setup Qt Creator for Raspberry Pi cross compilation – [Host]