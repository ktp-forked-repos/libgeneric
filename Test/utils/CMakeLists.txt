add_executable(swap_ints swap_ints.c)
target_link_libraries(swap_ints generic)

add_executable(search_ints search_ints.c)
target_link_libraries(search_ints generic)

enable_testing()

add_test(swap_ints swap_ints)
add_test(search_ints search_ints)
