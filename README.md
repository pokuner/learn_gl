### BUILD
1. git clone https://github.com/pokuner/learn_gl.git
2. cd learn_gl && mkdir build install
3. git submodule init
4. git submodule update
5. cd build && mkdir glfw && cd glfw
6. cmake -DCMAKE_INSTALL_PREFIX=../../install/GLFW ../../3rd/glfw