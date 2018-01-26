#add directory
	INCLUDE_DIRECTORIES (${HELLO_SOURCE_DIR}/lib)
	LINK_DIRECTORIES (${HELLO_BINARY_DIR}/lib)
#add executable target
	ADD_EXECUTABLE (hello main.c)
#link library
	TARGET_LINK_LIBRARIES (hello hello_lib)
