cmake_minimum_required(VERSION 3.15)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(trie)
set(SOURCE_DIR src)

# file(GLOB_RECURSE SOURCES "${SORUCE_DIR}/implement/*.cpp")
# add_library(${PROJECT_NAME} INTERFACE)

install(DIRECTORY ${SOURCE_DIR}/include/ DESTINATION include)