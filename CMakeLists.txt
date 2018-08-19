cmake_minimum_required(VERSION 3.0)

project(learn_gl)

include_directories(install/GLFW/include 3rd 3rd/glad/include)
link_directories(install/GLFW/lib)

aux_source_directory(src SRC_LEARN_GL)
aux_source_directory(3rd/glad/src SRC_LEARN_GL)

add_executable(learn_gl ${SRC_LEARN_GL})
target_link_libraries(learn_gl glfw3)