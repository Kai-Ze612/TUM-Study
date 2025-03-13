## Get Homework files
git clone git@cppprog.db.in.tum.de:assignments/ge62meq/a03 

## Check Homework points
ssh git@cppprog.db.in.tum.de points

## Build Docker file
docker build -t your-image-name .

docker run --rm -v "$PWD/:/homework" <image-name> "/homework/assessment.sh"

## CMake
nano CMakeLists.txt

cmake_minimum_required(VERSION 3.10)
project(HelloWorldProject)

### Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

### Add the executable
add_executable(helloworld main.cpp)

## Make c++ format
# To reorgainze the C++ formate
 clang-format -i mandelbrot.cpp
