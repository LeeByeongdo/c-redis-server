cmake_minimum_required(VERSION 3.24)
project(redis)

set(CMAKE_CXX_STANDARD 17)

#add_executable(redis main.cpp hashtable.cpp hashtable.h avl.cpp test_avl.cpp)
add_executable(redis main.cpp zset.cpp zset.h avl.cpp avl.h hashtable.cpp hashtable.h common.h list.h heap.h heap.cpp thread_pool.h thread_pool.cpp)
