add_executable(chcl_tests)

target_sources(chcl_tests
	PRIVATE
		Main.cpp
		Asserts.h
)

add_subdirectory(tests)
