cd build

cmake -G "MinGW Makefiles" -DCMAKE_INSTALL_PREFIX=../../install ..

make
make install

