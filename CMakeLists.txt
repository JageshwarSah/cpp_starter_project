cmake_minimum_required(VERSION 3.16)


if(MSVC)
	add_compile_options(/W4)
else()
	add_compile_options(-Wall -Wextra)
endif()

add_executable(intro main.cpp)
