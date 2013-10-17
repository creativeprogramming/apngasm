apngasm
=======
apngasm, the APNG Assembler
A set of libraries and a command line tool to assemble and disassemble APNG images.

Building
--------
apngasm uses CMake to provide cross platform build chains.

For all systems first clone the repository then enter the repository directory in 

Building on (Ubuntu/Debian) Linux:  

1. Install dependencies/build chain
```
sudo apt-get install cmake libpng-dev libboost-program-options-dev libboost-regex-dev
```

2. Generate makefiles with cmake  
```
cmake ./
```

3. Make  
```
make
```

Building on OS-X (with homebrew):  

1. Install cmake and libpng  
```
brew install cmake libpng lzlib
```

2. Generate makefiles with cmake  
```
cmake ./
```

3. Make  
```
make
```
  
Building on Windows (with Visual Studio 2012):  
1. Install cmake  
2. Generate VS project files  
3. Open VS project files in Visual Studio  
4. Hit build  
  
Libraries will be found in the lib directory.  
The apngasm command line tool can be found in the bin directory.

License
-------
zlib/libpng

Copyright
---------
This version of apngasm is a joint production by Genshin Souzou Kabushiki Kaisha and Max Stepin.
The original apngasm [found in the /legacy directory] is wholly copyright Max Stepin.
