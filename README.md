# Face-Detection-using C++.
Face-Detection  using C++ on visual studio 2019 .
Download opencv .
Download haarcascade_frontalface_default.xml 
open studio and create new project.
#steps to follows  
opencv version 3.4.14 
1]make in debug and 64x
2]create c++ source file 
3]open project--> properties
4]click on c/c++ ---> general -->additional include directories  add  D:\opencv\build\include
   4.1]preprocessor --->preprocessor definitions-->type _CRT_SECURE_NO_WARNINGS
5]click on linker--->general---->additional library directories--> add   D:\opencv\build\x64\vc15\lib
           linker-->input additional dependencies :---opencv_world3414d.lib
 and run the code
