cmake_minimum_required(VERSION 3.16)
project(book-mastering-opencv4)

set(TARGET_NAME ${PROJECT_NAME})

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(${TARGET_NAME} main.cpp)
set_property(TARGET ${TARGET_NAME} PROPERTY CXX_STANDARD 17)
target_link_libraries(${TARGET_NAME} ${CONAN_LIBS})

