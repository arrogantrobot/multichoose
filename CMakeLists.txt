cmake_minimum_required(VERSION 2.8)

add_library(multichoose
	multichoose.cpp
	multipermute.cpp
)

add_executable(multichoose-bin
	multichoose.cpp
)

set_target_properties(multichoose-bin
	PROPERTIES OUTPUT_NAME multichoose
)

add_executable(multipermute
	multipermute.cpp
)

add_executable(cmultichoose
	multichoose.c
)
