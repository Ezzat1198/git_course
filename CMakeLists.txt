cmake_minimum_required(VERSION 3.10)

project(git_learn)

file(GLOB_RECURSE SOURCE_FILES  src/*.cpp)
add_executable(main ${SOURCE_FILES})

target_include_directories(main PUBLIC include)