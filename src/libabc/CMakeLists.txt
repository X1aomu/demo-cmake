project(abc)

add_library(${PROJECT_NAME})

target_include_directories(${PROJECT_NAME} SYSTEM INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

target_sources(${PROJECT_NAME} PRIVATE
    abc.h
    abc.cpp
)