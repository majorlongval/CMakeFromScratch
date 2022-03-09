# CMakeFromScratch
The point of this repo is to create a default cpp project that uses CMAKE from scratch. The structure of the project should have the same structure as the one suggested in the book modernCmake. I will try to have as many commits as possibleso to have a clear evolution in the code.

The structure of the project is as follows:
CMakeFromScratch
 CmakeLists.txt
 - build (This folder contains all the junk that come out of CMAKE to make compiling and building (whatever the difference is haha)).
 - include (This folder contains all the header files for the classes in the src folder)
 - src (Contains all the source files for the classes and the main file)
 - bin (This folder contains all the executables that will come out of the project, for app). Dont know what to do for a lib cause im not there yet.
 - tests (This folder contains an executable for tests called test.cpp. Could be more but thats it for the moment)
 - extern (This folder contains external libraries that are used for the code. They should be packaged as a git submodule in order to be able to bring them to git (thats what i understand at least).
 - README.md
 - LICENSE.md


