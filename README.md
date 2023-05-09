# Glyfo Command Line Tool for Computer Vision.

glyclt-cv handler communication with Container to support Computer Vision Development.

Use emscripten to compile computer vision applications using OpenCV APIs.
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
+ setup  : manage CV container 
     + build  : deploy & install enviroment to develop using OpenCV 
     + status : validate if CV container is running on enviroment 
     + reset  : restart container ( stop & start ) 
     + info   : show version about software stack
     + login  : login into container
     + delete : delete CV container
     + backup : export CV container
v0.4.3

...
```

## 2- Setup 

```bash
$ glyclt-cv setup build # this command building & setup container 
$ glyclt-cv setup stack
----------------------- Release  --------------------
git       | 2.30.2
```
## 3 - Develop 

```bash
COMMING SOON 
```

## Reference

[OpenCV](https://opencv.org/)

[Docker](https://docker.com)
 

