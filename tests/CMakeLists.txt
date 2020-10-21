project(tests)

add_subdirectory(googletest)

add_executable(tests LinkedList.cpp)
target_link_libraries(tests gtest gtest_main linked-list)