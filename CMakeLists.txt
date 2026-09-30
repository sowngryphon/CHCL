cmake_minimum_required(VERSION 4.3)
project(CHCL)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

option(TESTS "Build CHCL tests" OFF)

add_library(chcl)

target_compile_features(chcl
	PUBLIC
		cxx_std_20
)

target_include_directories(chcl
	PUBLIC
	"${CMAKE_CURRENT_SOURCE_DIR}/"
)
add_subdirectory(chcl)

if (TESTS)
	add_subdirectory(tests)
endif()
