# CMake Cookbook

<a href="https://www.packtpub.com/application-development/cmake-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788470711"><img src="https://www.packtpub.com/sites/default/files/B08515.png" alt="CMake Cookbook" height="256px" align="right"></a>

This is the code repository for [CMake Cookbook](https://www.packtpub.com/application-development/cmake-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788470711), published by Packt.

**Building, testing, and packaging modular software with modern CMake**

## What is this book about?
CMake is cross-platform, open-source software for managing the build process in a portable fashion. This book features a collection of recipes and building blocks with tips and techniques for working with CMake, CTest, CPack, and CDash.

This book covers the following exciting features:
* Configure, build, test, and install code projects using CMake
* Detect operating systems, processors, libraries, files, and programs for conditional compilation
* Increase the portability of your code
* Refactor a large codebase into modules with the help of CMake
* Build multi-language projects

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1788470710) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter01.

The code will look like the following:
```
cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

project(recipe-01 LANGUAGES CXX)

add_executable(hello-world hello-world.cpp)
```

**Following is what you need for this book:**
If you are a software developer keen to manage build systems using CMake or would like to understand and modify CMake code written by others, this book is for you. A basic knowledge of C++, C, or Fortran is required to understand the topics covered in this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-15).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1-15     | CMake >= 3.5 g++ supporting C++11 gcc supporting C99 gfortran Windows: msys2 installer or Visual Studio | All chapters: Linux, macOS, and Windows except chapters 14 and 16 (only Linux and macOS) |
| 2        | Eigen 3.3.4           | |
| 3        | Python interpreter Python development libraries BLAS LAPACK MPI library Eigen 3.3.4 Boost 1.59 ZeroMQ | |
| 4        | Boost 1.54 Catch2 Google Test     | |
| 5        | Python interpreter Python development libraries BLAS LAPACK            | |
| 6        | Python interpreter Git            | |
| 8        | Boost 1.54 FFTW3 Eigen 3.3.4      | |
| 9        | LAPACK Python interpreter Python development libraries Cython Boost 1.54 CFFI pybind11 | |
| 11       | CFFI Anaconda pybind11            | |
| 12       | Doxygen Sphinx Breathe            | |
| 13       | MXE Visual Studio                 | |
| 14       | CDash                             | |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://www.packtpub.com/sites/default/files/downloads/CMakeCookbook_ColorImages.pdf).

### Related products
* Mastering Qt 5 - Second Edition [[Packt]](https://www.packtpub.com/web-development/mastering-qt-5-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788995399) [[Amazon]](https://www.amazon.com/dp/1788995392)

* Learn QT 5 [[Packt]](https://www.packtpub.com/web-development/learn-qt-5?utm_source=github&utm_medium=repository&utm_campaign=9781788478854) [[Amazon]](https://www.amazon.com/dp/1788478851)

## Get to Know the Authors
**Radovan Bast** works at the High Performance Computing Group at UiT - The Arctic University of Norway in Tromsø and leads the CodeRefinery project. He has a PhD in theoretical chemistry and contributes to a number of quantum chemistry programs as a code developer. He enjoys learning new programming languages and techniques, and teaching programming to students and researchers. He got in touch with CMake in 2008 and has ported a number of research codes and migrated a number of communities to CMake since then.

**Roberto Di Remigio** is a postdoctoral fellow in theoretical chemistry at UiT - The Arctic University of Norway in Tromsø, Norway and Virginia Tech, USA. He is currently working on stochastic methods and solvation models. He is a developer of the PCMSolver library and the Psi4 open source quantum chemistry program. He contributes or has contributed to the development of popular quantum chemistry codes and libraries: DIRAC, MRCPP, DALTON, LSDALTON, XCFun, and ReSpect. He usually programs in C++ and Fortran.

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
