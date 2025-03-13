#update when src files are added

add_executable(glfw_project main.c)

target_link_libraries(glfw_project OpenGL::GL glfw)
