# Poppler shared libraries for MinGW64
Includes a shared library linked test program in windows with MinGW64 compiler. All shared libraries are prebuilt and included with the executable. 

Features demonstrated:
* Open PDF
* print meta fields
* print full text
* print text list

Code is adapted from https://github.com/jeroen/popplertest

Sources:
* MSYS2 (https://msys2.duckdns.org/package/mingw-w64-x86_64-poppler?repo=mingw64)

Compiler: 
- gcc (x86_64-posix-seh-rev0, Built by MinGW-W64 project) 8.1.0

IDE: 
* Eclipse IDE for C/C++ Developers
	* Version: 2018-09 (4.9.0)
	* Build id: 20180917-1800

Library: 
* poppler 0.82.0-1
