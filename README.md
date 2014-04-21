A nice screenshooter written in python.


This is a fork of https://github.com/linuxdeepin-packages/deepin-scrot

# Features added:

1. allow user to select filename on commandline through the -o option
2. fixed the bug: regional screenshot includes the selection frame in the filnal image

# User's guide
* First generate mo files.
  Swith `deepin-scrot` directory to execute updateTranslate.sh like below:
      ./updateTranslate.sh

* Quick start:
  Switch `src` directory to execute deepinScrot.py like below command:
      cd ./src && ./deepinScrot.py
