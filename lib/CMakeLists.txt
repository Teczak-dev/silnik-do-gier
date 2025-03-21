add_library(mylib lib.cpp)

target_include_directories(mylib INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

# PRIVATE - cpp file only
# PUBLIC - use both cpp and h files
# INTERFACE - using only h file
