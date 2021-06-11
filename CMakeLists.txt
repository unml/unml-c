
cmake_minimum_required(VERSION 3.2)

project(unmlc
	VERSION 0.1
	LANGUAGES C
)

include_directories(include)

file(GLOB libunml_sources src/*.c)
add_library(unmlc
	${libunml_sources}
)


