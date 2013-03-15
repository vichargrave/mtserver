mtserver
========

Example source code for the article 'Multithreaded Work Queue Based Server in C++'

Build
=====

1. Get the threads code at https://github.com/vichargrave/threads.git.
2. Get the work queue code at
3. Get the TCP sockets code at
4. Place the mtserver, threads, wqueue and tcpsockets directories at the same directory 
   level, e.g. ${HOME}/src/mtserver, ${HOME}/src/threads, etc.
5. cd to ${HOME}/src/mtserver.
6. Build the test client and server applications by running 'make'.