# You can call cmake from command line by toolchain file argument   use `-DCMAKE_TOOLCHAIN_FILE=cmake/gcc.cmake`

# Project minimum version
cmake_minimum_required(VERSION 3.16.4)

include(Config.cmake)

enable_language(C ASM)

# Project name
project(EK_RA2L1_Blinky_CMake VERSION 1.0.0)

include(${CMAKE_CURRENT_LIST_DIR}/cmake/GeneratedSrc.cmake)
