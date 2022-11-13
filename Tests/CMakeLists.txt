project(Tests)

add_subdirectory(googletest)
include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(Tests MyTests.cpp)
target_link_libraries(Tests gtest gtest_main)