cmake_minimum_required(VERSION 3.2.0)
project(abc)
add_compile_options(-std=c++11)
message(WARNING "This is Top CMakeLists!")
message(${PROJECT_BINARY_DIR})

set(CMAKE_CXX_STANDARD 11)
set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin)

include_directories(${PROJECT_SOURCE_DIR}/include_test)
link_directories(${PROJECT_BINARY_DIR}/lib)

# go to sub dir to make
add_subdirectory(libs_test)
add_subdirectory(src_test)

