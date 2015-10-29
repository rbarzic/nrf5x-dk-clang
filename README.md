# nrf5x-dk-clang
A example of nRF51-DK/nRF52-DK  application using clang/llvm (under construction)



Note :
newlib installation :
wget ftp://sources.redhat.com/pub/newlib/newlib-2.2.0-1.tar.gz
tar xvzf newlib-2.2.0-1.tar.gz 
cd newlib-2.2.0-1/
./configure --target arm-none-eabi --disable-newlib-supplied-syscalls --prefix=/opt/newlib/2.2.0-1
make
sudo make install

