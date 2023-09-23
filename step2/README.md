# Step 2

https://kamino.hatenablog.com/entry/cmake_tutorial2

## How to run?

```bash
$ mkdir build
$ cd build/
$ cmake ..
-- The CXX compiler identification is GNU 11.4.0
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Check for working CXX compiler: /usr/bin/c++ - skipped
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring done
-- Generating done
-- Build files have been written to: /home/tomoya/blog_cmake_tutorial/step2/build
$ cmake --build .
[ 25%] Building CXX object uftree/CMakeFiles/uftree.dir/src/uftree.cpp.o
[ 50%] Linking CXX static library libuftree.a
[ 50%] Built target uftree
[ 75%] Building CXX object CMakeFiles/main_app.dir/main.cpp.o
[100%] Linking CXX executable main_app
[100%] Built target main_app
$ ./main_app
same(1, 2) : False
size(3) : 2
Groups :
0,2,4,
1,3,
```
