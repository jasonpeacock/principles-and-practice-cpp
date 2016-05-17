cmake_minimum_required (VERSION 3.4)
project (principles-and-practice-cpp)

include_directories("${PROJECT_SOURCE_DIR}/include")

########################################################
# chapter 2
########################################################
file(GLOB CHAPTER_2_SOURCES "${PROJECT_SOURCE_DIR}/chapter_2/*.cpp")
add_executable(hello_world ${CHAPTER_2_SOURCES})

