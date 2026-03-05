cmake_minimum_required(VERSION 3.10)

project(myproject)

add_executable(myprog
                      src/main.cpp
                       src/executer.cpp
			src/parser.cpp
			src/builtins.cpp
)

target_include_directories(myprog PUBLIC include)
