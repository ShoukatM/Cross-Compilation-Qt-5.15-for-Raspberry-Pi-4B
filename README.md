# Cross-Compiling-Qt-5.15.0-for-Raspberry-Pi-4


This is a guide for Cross-compiling Qt 5.15 for a Raspberry Pi 4 running Ubuntu
20.04 Server from a host machine running Ubuntu 20.04.
Tested with below prerequisite.

Hardware:
Host: 12th Gen Intel® Core™ i5-1235U × 12
Target: Raspberry Pi 4 Model B

Software:
Host: Ubuntu 20.04 LTS
Target: OS Ubuntu 20.04 Server
Cross Compiler:gcc-linaro-7.5.0-2019.12-x86_64_arm-linux-gnueabihf.tar.xz

It is assumed that you have a SD card with ubunutu 20.04 Server installed in
your Raspberry Pi, otherwise download it and follow the installation guide.
we have downloaded the image and prepared the SD card on Ubuntu machine.
The following list summarizes the main steps to cross-compile Qt 5.12 for
Raspberry Pi, we will be describing each of them in this guide.

1. Flash the image onto on SD card
2. Update the system with the following commands-[RPI4]
3. Install development libraries-[RPI4]
4. Prepare target folder –[RPI4]
5. Prepare Ubuntu Host Machine –[Host]
6. Create working folder download QT Resources and set a toolchain–
[Host]
7. Create and configure a sysroot [Host]
8. Configure Qt for cross compilation –[Host]
9. Setup Qt Creator for Raspberry Pi cross compilation

