project(Almond)

add_library(
    ${PROJECT_NAME} SHARED 
    src/Almond/Test.cpp
    )

target_include_directories(
    ${PROJECT_NAME} PUBLIC
    "${CMAKE_CURRENT_SOURCE_DIR}/src"
    )

