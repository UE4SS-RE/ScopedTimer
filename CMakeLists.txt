cmake_minimum_required(VERSION 3.18)

set(TARGET ScopedTimer)
project(${TARGET})
message("Project: ${TARGET} (HEADER-ONLY)")

add_library(${TARGET} INTERFACE)
target_include_directories(${TARGET} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
