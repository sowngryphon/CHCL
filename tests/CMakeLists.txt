add_executable(chcl_tests)

target_link_libraries(chcl_tests
	PRIVATE
		chcl
)

target_sources(chcl_tests
	PRIVATE
		Main.cpp
		Asserts.h
)

add_subdirectory(tests)
