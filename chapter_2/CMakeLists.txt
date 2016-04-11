cmake_minimum_required (VERSION 3.4)
project (chapter_2)

#find_library(LIBSTDCXX stdc++)

include_directories("${PROJECT_SOURCE_DIR}/../include")
add_executable(hello_world hello_world.cpp)

#set_property(TARGET hello_world PROPERTY CXX_STANDARD 11)
#set_property(TARGET hello_world PROPERTY CXX_STANDARD_REQUIRED ON)
#target_link_libraries(hello_world ${LIBSTDCXX})
