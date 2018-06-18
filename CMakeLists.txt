cmake_minimum_required(VERSION 3.6)
project(conanboosttemplate)
set(CMAKE_CXX_STANDARD 11)

include(conanbuildinfo.cmake)
conan_basic_setup()

set(SOURCE_FILES main.cpp)
add_executable(conanboosttemplate ${SOURCE_FILES})
target_link_libraries(conanboosttemplate ${CONAN_LIBS})
