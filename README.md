# SMILE therapy

OpenCV cpp 예제 파일에 있는 웃음 탐지기 입니다.  
카운트 횟수를 추가하여 웃음 탐지 횟수를 측정합니다.

## Setting

1. 윈도우일 경우 OpenCV 설치 후 [환경 변수](https://3001ssw.tistory.com/162) 작업이 필요합니다.  

2. 리눅스일 경우 Command 환경에서 openCV를 설치합니다. 

## Environment

`windows`, `Linux`

## Run

### Compile
```
$ g++ -o SMILE_count opencv_smile.cpp $(pkg-config opencv4 --libs --cflags)
```
### Build
```
$ ./SMILE_count --cascade="/usr/local/share/opencv4/haarcascades/haarcascade_frontalface_alt.xml" --smile-cascade="/usr/local/share/opencv4/haarcascades/haarcascade_smile.xml" --scale=1.3
```
`Windows` : Visual Basic Studio에서 실행합니다.  
`Linux`   : Terminal에서 실행합니다.
