cmake_minimum_required(VERSION 4.3)
project(CHCL)

add_library(chcl)

target_compile_features(chcl
	PUBLIC
		cxx_std_20
)

target_include_directories(chcl
	PUBLIC
	"${CMAKE_SOURCE_DIR}/"
)
add_subdirectory(chcl)
