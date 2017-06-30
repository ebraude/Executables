# Executables
The following repository contains Geopar 
([https://github.com/ebraude/geopar](https://github.com/ebraude/geopar)) 
that is compiled using Pyinstaller ([http://www.pyinstaller.org](http://www.pyinstaller.org)) 
and can be run without having to worry about dependencies on Windows, MacOS, and Linux platforms. 

## Downloading files
Click **Clone or download** and then **Download ZIP** buttons on 
[https://github.com/ebraude/Executables](https://github.com/ebraude/Executables).
This will download all the files as a zip archive. Unpack the archive. 

## Running on Windows
Windows executables are located in a folder **Windows**.
The folder contains various library files, _input.txt_, and _run.exe_.
_input.txt_ contains all Triangulated Figure configurations. 
The configuration of interest should be moved to the top in _input.txt_, 
since Geopar runs only one configuration. 

To run Geopar:
1. Open Windows Command Prompt (cmd)
2. Navigate to the **Windows** folder
3. Type `run.exe` to run the executable

## Running on Mac and Linux
Mac and Linux executables are located in a folder **Mac, Linux**. 
_input.txt_ contains all Triangulated Figure configurations. 
The configuration of interest should be moved to the top in _input.txt_, 
since Geopar runs only one configuration. 

To run Geopar: 
1. Open Terminal
2. Navigate to the **Mac, Linux** folder
3. Type `./run` to run the executable