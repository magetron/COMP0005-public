# Coursework 2 Question 2

```
.
├── Pair1
│   ├── disparity-0.384.png
│   ├── disparity-3.84.png
│   ├── disparity-38.4.png
│   ├── disparity1.png
│   ├── left1.png
│   └── right1.png
├── Pair2
│   ├── disparity2.png
│   ├── left2.png
│   └── right2.png
├── Pair3
│   ├── disparity3.png
│   ├── left3.png
│   └── right3.png
├── Pair4
│   ├── disparity4.png
│   ├── left4.png
│   └── right4.png
├── README.md
└── RamdomDots
    ├── disparity.png
    ├── left.png
    └── right.png
```   


## Instructions
See Appendix 3.2 for source code.

### Pre-requisites
`clang` with C++11 support

`opencv 4.0.1`

### To generate a disparity map for two images (same size)
Compile with `clang++ -std=c++11 $(pkg-config --cflags --libs opencv4) Q2.cc` andexecute `./Q2.out LEFT_IMG_FILENAME RIGHT_IMG_FILENAME`.

### To generate a random dot test case
Compile with `g++ -std=c++11 $(pkg-config --cflags --libs opencv4) generate-img.cc -o generate-img.out` and execute `./generate-img.out`.

See `left.png` and `right.png` under the same folder the the program.
