project(Sandbox)

add_executable(${PROJECT_NAME}
    src/Application.cpp)
    
target_link_libraries(Sandbox PRIVATE Almond)
