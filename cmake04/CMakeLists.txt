PROJECT(HELLOFUNC)

MESSAGE(STATUS "\t测试->" ${HELLOFUNC_BINARY_DIR})
MESSAGE(STATUS "\t源文件->" ${HELLOFUNC_SOURCE_DIR})
MESSAGE(STATUS "\t安装文件前缀->" ${CMAKE_INSTALL_PREFIX})

ADD_SUBDIRECTORY(lib bin)
