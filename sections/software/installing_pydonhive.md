$order=0
$title=Installing the python software

The python software enables you to communicate with the MiniBees. It takes care of the configuration of the MiniBees, and sends OpenSoundControl data to your preferred software, for example PureData, SuperCollider, Processing, Max/MSP, vvvv, Isadora.

###Installation on Linux

- Download the [source package](https://github.com/sensestage/ssdn_python/archive/master.zip).
- Unpack the package (in the file manager: double-click, or right-click menu “extract here”).
- Open a terminal and go to the directory where you unpacked the package.
- Run the ```./installation.sh``` script that is in the package (as root).

*Note for Ubuntu users: you will need both the python and python-tk package installed from the package manager*


Alternatively do the following all in the terminal:

    wget https://github.com/sensestage/ssdn_python/archive/master.zip
    unzip master.zip
    cd ssdn_python-master/
    sudo ./installation.sh

###Installation on OSX

- Download the [source package](https://github.com/sensestage/ssdn_python/archive/master.zip).
- Unpack the package (in the file manager: double-click, or right-click menu “extract here”).
- Open a terminal and go to the directory where you unpacked the package.
- Run the ```./installation.sh``` script that is in the package.

###Installation on Windows

- Download the [pydon package for windows](https://sensestage.eu/downloads/PydonWindowsPackage.zip)
- Download and install [Windows usb serial driver](http://arduino.cc/en/Guide/Windows#toc4)
- Install latest python for windows using the msi installer (32 bit or 64 bit). Just doubleclick and follow instructions, select to add python.exe to the path, otherwise just follow the default suggestions.
- Execute the ```install_pydon.bat``` file by doubleclicking
- Execute the ```start_pydon.bat``` file by doubleclicking to start pydongui

