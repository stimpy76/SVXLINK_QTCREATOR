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
12) Install popt dev pack<br>
    sudo apt-get install libpopt-dev
13) Install gcrypt dev pack<br>
    sudo apt-get install libgcrypt-dev
14) Install rtlsdr dev pack<br>
    sudo apt-get install librtlsdr-dev
15) Install tcl dev pack<br>
    sudo apt-get install tcl-dev
16) Install gsm dev pack<br>
    sudo apt-get install libgsm1-dev
17) Install qt5 dev packs<br>
    sudo apt-get install qttools5-dev qtbase5-dev qttools5-dev-tools
   
### Download en install QT framework

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
8) Don't start and press finish button

### Compiling with QTCreator

1) Start QTCreator
2) Open Project<br>
   goto /"File Location/svxlink/src/CMakeLists.txt
3) Open
4) Build<br>
   In the project folder on the left you get svxlink project right click on it and build
5) Feel free to change code.

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
   

   


