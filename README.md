# Simple Open EtherCAT Master Library
[![Build Status](https://travis-ci.org/OpenEtherCATsociety/SOEM.svg?branch=master)](https://travis-ci.org/OpenEtherCATsociety/SOEM)
[![Build status](https://ci.appveyor.com/api/projects/status/bqgirjsxog9k1odf?svg=true)](https://ci.appveyor.com/project/hefloryd/soem-5kq8b)

SHARED LIBRARY
========

This is a Fork of Simple Open EtherCAT Master Library
-----------------------------------------------------

 * This Fork is used to generate a Shared Library
   * .DLL for Windows
   * .a for Linux

 * Example API can be found here:
[Python](https://github.com/GitHubStefan13/SOEM-for-Python)
[Lazarus](https://github.com/GitHubStefan13/SOEM-for-Pascal)

BUILDING
========


Prerequisites for all platforms
-------------------------------

 * CMake 2.8.0 or later


Windows (Visual Studio)
-----------------------

 * Start a Visual Studio command prompt then:
   * `mkdir build`
   * `cd build`
   * `cmake .. -G "NMake Makefiles"`
   * `nmake`

Linux
-----

   * `mkdir build`
   * `cd build`
   * `cmake ..`
   * `make`

Want to contribute to SOEM or SOES?
-----------------------------------

Check the Master for more information [Master](http://openethercatsociety.github.io/cla/cla_soem_soes.pdf).
