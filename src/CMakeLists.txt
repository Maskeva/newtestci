project(test)

include_directories(../include)

set(CMAKE_BUILD_TYPE Release)

# MESSAGE(STATUS "Current path : ${PROJECT_SOURCE_DIR}")

file(GLOB SOURCES *.cpp)

add_executable(${PROJECT_NAME} ${SOURCES}) 