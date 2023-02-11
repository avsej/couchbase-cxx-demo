cmake_minimum_required(VERSION 3.17)
project(couchbase_cxx_demo VERSION "1.0.0" LANGUAGES CXX)

add_executable( travel main.cxx)
target_link_libraries( travel ${CMAKE_THREAD_LIBS_INIT})
