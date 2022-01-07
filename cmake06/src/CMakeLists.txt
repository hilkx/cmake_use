INCLUDE_DIRECTORIES(D:/study/cmake_use/install/include/hello)

LINK_DIRECTORIES(D:/study/cmake_use/install/lib)

#LINK_LIBRARIES(hello)
ADD_EXECUTABLE(main main.cpp)
TARGET_LINK_LIBRARIES(main hello)

