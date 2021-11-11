# SMILE therapy

This is a laughter detector in the OpenCVcpp example file.  
Measure the number of laughter detections by adding counts.

## Setting

1.If it is a windows, [environmental variable](https://3001ssw.tistory.com/162) operation is required after installing opencv.

2.In the case of Linux, install opencv in the command environment.

## Environment

`Windows`, `Linux`

## Run

### Compile
```
$ g++ -o SMILE_count opencv_smile.cpp $(pkg-config opencv4 --libs --cflags)
```
### Run
```
$ ./SMILE_count --cascade=model/haarcascade_frontalface_alt.xml --smile-cascade=model/haarcascade_smile.xml --scale=1.3
```
or
```
$ ./run.sh
```
`Windows`: Visual Basic Studio.  
`Linux`: It's a terminal.
