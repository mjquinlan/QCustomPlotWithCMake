# QCustomPlotWithCMAKE
A repository for building visualizations using QCustomPlot managed by CMAKE

I needed to integrate QCustomPlot visualizations into a larger Windows 64bit Visual Studio project that relies on CMAKE. This is a stub project that builds a basic program using CMAKE to help others facing similar integration tasks.

# Build
Note: I use git shell (wrapped powershell) syntax, since I'm a believer in bash

$ cd $QCustomPlotWithCMAKEROOT
$ mkdir build64; cd build64
$ cmake -DCMAKE_PREFIX_PATH=C:\Qt\5.4\msvc2013_64\ ../src -G "Visual Studio 11 Win64"



