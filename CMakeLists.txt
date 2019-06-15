cmake_minimum_required(VERSION 3.14)
project(alsalearn C)

set(CMAKE_C_STANDARD 99)

# sudo apt install libasound2-dev

add_executable(alsalearn main.c)
target_link_libraries(alsalearn asound)
