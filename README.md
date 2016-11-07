# mtserver

Example code from my Multithreaded Work Queue Based Server in C++ blog.

# Build

1. Get the [threads](https://github.com/vichargrave/threads.git) code.
2. Get the [work queue](https://github.com/vichargrave/wqueue) code.
3. Get the [TCP sockets](https://github.com/vichargrave/tcpsockets) code.
4. Place the mtserver, threads, wqueue and tcpsockets directories at the 
   same directory level, e.g. `${HOME}/src/mtserver`, `${HOME}/src/threads`, 
   `${HOME}/src/wqueue` and `${HOME}/src/tcpsockets`.
5. cd to `${HOME}/src/mtserver`.
6. Build the test client and server applications by running `make`.
