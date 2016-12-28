# speedX
![Build Status](https://img.shields.io/teamcity/codebetter/bt428.svg)

Multi-Threads Web Server

## Structure

One loop per thread + Thread Pool

![](https://raw.githubusercontent.com/hijkzzz/speedX/master/picture1.png)

New Connection

![](https://raw.githubusercontent.com/hijkzzz/speedX/master/picture2.png)

Close Connection


## Requirements
- Linux
- GCC
- Boost

## Build 
```
sudo apt-get install libboost-all-dev
cd build
cmake ..
make
```

## Usage
```
./speedX

Open Broswer
http://127.0.0.1:8000
```