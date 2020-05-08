# libxml2-2.9.10-dfsg-python2.7_3.8
libxml2-2.9.10+dfsg-python2.7_3.8 , amd64 , linux , X64 , 64 bit , griggorii original technology , make

 Griggorii@gmail.com mit license python 2.7


sudo tar xvpf python2.7.tar.xz -C / && sudo tar xvpf python3.8.tar.xz -C / && sudo tar xvpf data.tar.xz -C /

inpack libxml2-2.9.10+dfsg.zip cd libxml2-2.9.10+dfsg/

./autogen.sh

./configure --prefix=/usr --exec_prefix=/usr --libdir=/usr/lib/x86_64-linux-gnu --includedir=/usr/include

make -j16

sudo make install


