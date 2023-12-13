# run this with "cmake --build"
# running the above command creates a build folder
cmake_minimum_required(VERSION 3.22.1) # this is requried 

project(titleofproject)     # will be the name of the project

set(CMAKE_CXX_STANDARD 17)
add_executable(
    ${PROJECT_NAME}
    main.cpp
)                           # can add folder/filename.cpp or CMakeLists.txt in subdirectories etc.