# SVXLINK_QTCREATOR
How to build SVXLINK with QTCREATOR

1) Install VirtualBox
2) Download latest Ubuntu desktop 18.04.1 LTS
3) Install latest Ubuntu on VirtualBox
4) Install Build-Essential<br>
   sudo apt-get install build-essential
5) Install Git<br>
   sudo apt-get install git
6) Install CMake<br>
   sudo apt-get install cmake
7) Install pkg-config<br>
   sudo apt-get install pkg-config
8) Install sigc++-2.0 dev pack<br>
   sudo apt-get install libsigc++-2.0-dev
9) Install speex dev pack<br>
   sudo apt-get install libspeex-dev
10) Install Opus dev pack<br>
   sudo apt-get install libopus-dev
11) Install Alsa dev pack<br>
   sudo apt-get install libasound2-dev
12) Download en install QT framework<br>
    1) Download QT<br>
       wget http://download.qt.io/official_releases/online_installers/qt-unified-linux-x64-online.run
    2) Chmod filename in terminal<br>
       chmod 775 /"File Location"/qt-unified-linux-x64-online.run
    3) Run installer<br>
       ./"File Location"/qt-unified-linux-x64-online.run
    4) Make QT account<br>
    5) Select Components<br>
       Picture
    6) Accept Licence Agreement
    7) Press Install button<br>
    Coffee this take some time :P


### Compiling without QTCreator

1) Make directory where clone SVXLink in to.<br>
   mkdir "name"
2) Change to directory<br>
   cd "name"
3) Clone SVXLink repositorie<br> 
   git clone http://github.com/sm0svx/svxlink.git
4) Change to directory svxlink/src/<br>
   cd /svxlink/src
5) Make building directory<br>
   mkdir build
6) Change to directory build<br>
   cd build
7) Run CMake command<br>
   cmake ../
   

   


