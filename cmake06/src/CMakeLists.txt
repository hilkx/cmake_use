INCLUDE_DIRECTORIES(../../install/include/hello)

LINK_DIRECTORIES(../../../install/lib)

#LINK_LIBRARIES(hello)
ADD_EXECUTABLE(main main.cpp)
TARGET_LINK_LIBRARIES(main hello)

