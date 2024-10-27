# ZenNotes-Windows-Binaries

This repository provides binaries for Rohan Kishore's Zen Notes software. It contains Windows Installers that can make installation a lot easier.

To download the source code, please visit the official repository [here](https://github.com/rohankishore/ZenNotes).

Usage:
1. Clone the official repository.
2. `cd` into the official repository, and then run the following commands to build the software:

Windows instructions (run as admin):
```
pip3 install -r requirements.txt
pyinstaller --onedir -w --icon="icon.ico" src\main.py
```

Unix instructions:
```
sudo pip3 install -r requirements.txt
pyinstaller --onedir -w --icon="icon.ico" src/main.py
```

pip3 install 0r requi
3. Download `zen-notes-x64.iss` from this repo, and put it in the root of the cloned main repo.
4. Compile the .iss file with Inno Setup.