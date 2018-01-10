SET(CMAKE_C_COMPILER "/usr/local/lib/gcc-7.2.0")
PROJECT (HELLO)


SET(SRC_LIST helloworld.c)
ADD_EXECUTABLE(hello helloworld.c)