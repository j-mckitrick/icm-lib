cmake_minimum_required(VERSION 2.6)

project(jcm)

add_library(jcm SHARED jcm.h jcm.c)

install(TARGETS jcm
		LIBRARY DESTINATION lib)
