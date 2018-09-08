# SVXLINK_QTCREATOR
How to build SVXLINK with QTCREATOR

1) Install VirtualBox
2) Download latest Ubuntu desktop 18.04.1 LTS
3) Install latest Ubuntu on VirtualBox
4) Install Build-Essential
   sudo apt-get install build-essential
5) Install Git
   sudo apt-get install git
6) Install CMake
   sudo apt-get install cmake
7) Install pkg-config
   sudo apt-get install pkg-config
8) Install sigc++-2.0 dev pack
   sudo apt-get install libsigc++-2.0-dev
9) Install speex dev pack
   sudo apt-get install libspeex-dev
10) Install Opus dev pack
   sudo apt-get install libopus-dev
11) Install Alsa dev pack
   sudo apt-get install libasound2-dev
12) Download en install QT framework
    1) Download QT
       wget http://download.qt.io/official_releases/online_installers/qt-unified-linux-x64-online.run
    2) Chmod filename in terminal
       chmod 775 /<file location>/qt-unified-linux-x64-online.run
    3) Run installer
       ./<file location>/qt-unified-linux-x64-online.run
    4) Make QT account
    5) Select Components
       Picture
    6) Accept Licence Agreement
    7) Press Install button



### Compiling without QTCreator

1) Make directory where clone SVXLink in to.
   mkdir <name>
2) Change to directory
   cd <name>
3) Clone SVXLink repositorie 
   git clone http://github.com/sm0svx/svxlink.git
4) Change to directory svxlink/src/
   cd /svxlink/src
5) Make building directory
   mkdir build
6) Change to directory build
   cd build
7) Run CMake command
   

   


