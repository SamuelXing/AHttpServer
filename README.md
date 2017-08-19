<p align="center">
    <h2 align="center">A tiny HTTP server</h2>
</p>

This software is originally copyright 1999 by J. David Blackstone. This is a simple project to help people understand the core concepts of a http server. 
The total project only contains around 500 lines of code. Amazing and impressive, isn't it? Based on the original code, from the perspectives of security and performance, I'll add new features includes: __SSL__, __asychronous requests__ and __multiprocess__. 

## Compile on Linux or MacOS
To compile for Linux:

1. Comment out the #include <pthread.h> line.
2. Comment out the line that defines the variable newthread.
3. Comment out the two lines that run pthread_create().
4. Uncomment the line that runs accept_request().
5. Remove -lsocket from the Makefile.

## HTTP Server

## Workflow

