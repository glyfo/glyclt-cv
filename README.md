# Glyfo Command Line Tool for Computer Vision.

glyclt handler communication with Container to support Computer Vision Development.

Using emscripten to compile computer vision applications using OpenCV APIs.
The applications can be deployed using Web Worker Technology, providing a robust and scalable solution for web-based 
computer vision tasks.

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Prerequisite 

+ Docker 
+ wget
+ MacOS ( x86_64 )

## 1- Install 

```bash
$ wget -O /usr/local/bin/glyclt-cv wget -O /usr/local/bin/glyclt-cv https://github.com/glyfo/glyclt-sui/releases/download/v0.3.3/glyclt-cv
$ chmod +x /usr/local/bin/glyclt-cv
$ ./glyclt-cv
 Usage:  glyclt-cv 
+ setup       : manage CV container 
     + status   : validate if suiX is running on enviroment 
     + build    : deploy & install enviroment to develop using sui blockchain 
     + login    : login into container 
     + reset    : restart container ( stop & start ) 
     + info     : show version about software stack 
     + backup   : export CV container
     + delete   : delete container

v0.4.3

...
```

## 2- Setup 

```bash
$ glyclt-cv setup build # this command building & setup container 
$ glyclt-cv setup stack
----------------------- Release  --------------------
git       | 2.30.2
rustc     | 1.64.0
cargo     | 1.64.0
sui       | 0.10.0
```
## 3 - Develop 

```bash
COMMING SOON 
```

## Reference

[OpenCV](https://opencv.org/)

[Docker](https://docker.com)
 

