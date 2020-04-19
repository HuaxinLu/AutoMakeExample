## 不必进行GNU规范检查
AUTOMAKE_OPTIONS=foreign
## 递归子目录
## SUBDIRS=
## 需要生成的bin文件
bin_PROGRAMS=mp3
## 需要的源文件
mp3_SOURCES=player.c
## 需要链接的库
mp3_LDADD=../usb/libusb.a ../lcd/liblcd.a ../media/libmedia.a ../lib/libgif.a
## 头文件目录
mp3_CFLAGS=-I../inc
## 链接动态库的目录
mp3_LDFLAGS=-L../math -L../lib
## 需要链接的动态库
LIBS=-lmath -lrmvb
## 需要打包的目录
##EXTRA_DIST=lib
