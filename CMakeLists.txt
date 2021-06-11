
cmake_minimum_required(VERSION 3.2)

project(unmlc
	VERSION 0.1
	LANGUAGES C
)

include_directories(include)

add_library(unmlc
	src/unml.c
	src/document.c
	src/element.c
)


