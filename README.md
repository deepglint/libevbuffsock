libevbuffsock is a minimal port of the evbuffer suite of functions from libevent to libev

mannuly build this project you should do like this 
cc -c *.c -g -Wall -O2 -fPIC 
ar rc libevbuffsock.a *.o
ranlib libevbuffsock.a

