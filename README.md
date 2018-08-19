### BUILD
1. git clone https://github.com/pokuner/learn_gl.git

#### 建立构建和安装目录
2. cd learn_gl && mkdir build install

#### 更新子模块glfw
3. git submodule init
4. git submodule update

#### 生成glfw的makefile
5. cd build && mkdir glfw && cd glfw
6. cmake -DCMAKE_INSTALL_PREFIX=../../install/GLFW ../../3rd/glfw

#### 生成learn_gl的makefile
7. cd .. && mkdir learn_gl && cd learn_gl
8. cmake ../../

9. 编译安装glfw
10. 编译learn_gl