CC=gcc
CFLAGS=-g 
ZOOKEEPER_INSTALL=/usr/local
ZOOKEEPER_INC=-I${ZOOKEEPER_INSTALL}/include/zookeeper
ZOOKEEPER_LIB= -L${ZOOKEEPER_INSTALL}/lib -lzookeeper_mt

APP=monitor
all:
	${CC} monitor.c -DTHREAD ${CFLAGS} ${ZOOKEEPER_INC} ${ZOOKEEPER_LIB} -o ${APP} 
clean:
	rm -f ${APP}
