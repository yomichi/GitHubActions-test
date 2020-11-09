configure_file(${CMAKE_CURRENT_SOURCE_DIR}/hello.sh.in ${CMAKE_CURRENT_BINARY_DIR}/hello.sh @ONLY)
add_test(NAME hello COMMAND sh ${CMAKE_CURRENT_BINARY_DIR}/hello.sh)
