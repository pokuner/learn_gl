### BUILD
1. git clone https://github.com/pokuner/learn_gl.git

#### ���������Ͱ�װĿ¼
2. cd learn_gl && mkdir build install

#### ������ģ��glfw
3. git submodule init
4. git submodule update

#### ����glfw��makefile
5. cd build && mkdir glfw && cd glfw
6. cmake -DCMAKE_INSTALL_PREFIX=../../install/GLFW ../../3rd/glfw

#### ����learn_gl��makefile
7. cd .. && mkdir learn_gl && cd learn_gl
8. cmake ../../

9. ���밲װglfw
10. ����learn_gl