# Coursework 2 Question 2

## Instructions

### To generate a disparity map for two images (same size)
Compile with `clang++ -std=c++11 $(pkg-config --cflags --libs opencv4) Q2.cc` andexecute `./Q2.out LEFT_IMG_FILENAME RIGHT_IMG_FILENAME`.

### To generate a random dot test case
Compile with `g++ -std=c++11 $(pkg-config --cflags --libs opencv4) generate-img.cc -o generate-img.out` and execute `./generate-img.out`.

See `left.png` and `right.png` under the same folder the the program.

## Pre-requisites

`clang` with C++11 support
`opencv 4.0.1`
