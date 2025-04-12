find_package(OpenGL REQUIRED) # OpenGL::GL
add_library(glad 
    ${CMAKE_CURRENT_LIST_DIR}/include/glad/glad.h
    ${CMAKE_CURRENT_LIST_DIR}/src/glad.c
)
target_include_directories(glad PUBLIC ${CMAKE_CURRENT_LIST_DIR}/include/)