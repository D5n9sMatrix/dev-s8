cmake_minimum_required(VERSION 3.0.0)
project(dev-s8 VERSION 0.1.0)

include(CTest)
enable_testing()

add_library(dev-s8 dev-s8.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
