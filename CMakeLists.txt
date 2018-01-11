SET(CMAKE_SYSTEM_NAME WindowsCE)
SET(CMAKE_C_COMPILER gcc)
PROJECT (HELLO)


SET(SRC_LIST file/helloworld.c)
ADD_EXECUTABLE(hello file/helloworld.c)
