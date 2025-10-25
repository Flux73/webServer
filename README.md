Webserv

A lightweight HTTP server implementation written in C++98.

Overview

Webserv is a custom HTTP server built from scratch in C++98, designed to handle HTTP requests and serve web content. This project demonstrates fundamental networking concepts and HTTP protocol implementation.

bash
make

This will create the webserv executable.

Available Make Targets

make or make all - Compile the server

make clean - Remove object files

make fclean - Remove object files and executable

make re - Rebuild the project from scratch

Usage

bash

./webserv [configuration_file]

The project is compiled with the following flags:

-std=c++98 - C++98 standard compliance

-fsanitize=address - Memory error detection (debug mode)

-g - Debug symbols

For production builds, consider removing the sanitizer flag and adding optimization flags like -O2.
