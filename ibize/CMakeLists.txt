cmake_minimum_required(VERSION 3.10)
project(IBIze)

set(CMAKE_CXX_STANDARD 11)

add_executable(ibize
	blockstream.cpp
	ibize.cpp
	interpreter.cpp
	md4.c
	tokenizer.cpp)
