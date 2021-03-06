==========================
Pegasus System - Description
==========================

Pegasus System has been designed by an experienced team of software developers 
and exploit writers to automate processes so penetration testers can focus 
on what's really important. The threat. This blend of software engineers and 
subject matter experts provides an unique advantage by combining technical 
know-how with true insight into the problem set, resulting in more efficient 
solutions for cyber security surveillance.

Happy hacking!

===============================
Get an ISO/VM with Pegasus System
===============================
Get an ISO or a VM with Pegasus System already installed: Pegasus System comes pre-installed in several Linux distributions, but our all time favorite is BlackArch, get it here: https://blackarch.org/downloads.html

========================
Get/Update using GIT
========================
After you install git in your desired platform, windows, osx, linux then you can simply run the following commands:

To get Pegasus System:
$ git clone https://github.com/sobri3195/pegasus-system.git

To update to the latest release:
Navigate into Pegasus System folder and run this command
$ git pull

========================
Documentation
========================
Please check our javadocs included under the folder with that name, also check our online guide, pdfs and the information all over the internet about this
tool, feel free to make comments, integrate with our community and have fun!

========================
Known issues:
========================
Using Pegasus System could produce addiction
Prolonged periods of time using this tool could produce network mayhem or even dead
In case of intoxication ( using Pegasus System under Windows ) please call your doctor immediately.

========================
License
========================
We believe in open source, and Pegasus System is no exception, it is licensed under GPLv3 and a copy of the license is attached in the source code.

========================
Installation notes:
========================

Windows:
Download and install Java 8 from Oracle:
Depending on your platform you have to choose between Windows Java SE Java 8 for 32 bits or Java 8 for 64 bits 
After you have installed Java 8 in your system, get Pegasus System from the official site, uncompress and 
double click ExplotPack.jar, if that does not work, try from a console using this command: "java -jar ExploitPack.jar"

Linux:
Under any Linux distribution that supports DEB packages like Ubuntu, Debian, Kali, etc. you can run the following commands to install Java 8 from an official repository 
Copy and paste the following in a terminal window:

sudo su -
cat >/etc/apt/sources.list.d/webupd8team-java.list<< EOF
deb http://ppa.launchpad.net/webupd8team/java/ubuntu trusty main
deb-src http://ppa.launchpad.net/webupd8team/java/ubuntu trusty main 
EOF
apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys EEA14886
apt-get update
apt-get install oracle-java8-installer
java -version

Then, get Pegasus System trough GIT or download it from the official website. After that run it from a terminal
using the following command: "java -jar ExploitPack.jar"

OSX:
Download and install Java 8 for OSX 32/64 bits from Oracle: OSX Java 8 32/64 bits
After you have Java 8 installed in your Mac, download Pegasus System, uncompress and double click ExploitPack.jar to run it or from a console: "java -jar ExploitPack.jar"

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "Pegasus-system.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

Https://www.terkoding.com