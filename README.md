# QCustomPlotWithCMAKE
A repository for building visualizations using QCustomPlot managed by CMake

For more information on QCustomPlot visit
http://qcustomplot.com/index.php/introduction

I needed to integrate QCustomPlot visualizations into a larger Windows 64bit Visual Studio project built with CMake. This is a stub project that builds the example programs program using CMake rather then qmake to help others facing similar integration tasks.

# How To Build
Note: I use git shell (wrapped powershell) syntax, since I'm a believer in bash

  $ cd GITCLONEDROOT
  
  $ mkdir build64; cd build64
  
  $ cmake -DCMAKE_PREFIX_PATH=C:\Qt\5.4\msvc2013_64\ ../src -G "Visual Studio 11 Win64"

