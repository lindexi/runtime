set(SOURCES
  findnextfilew.cpp
)

add_executable(paltest_findnextfilew_test2
  ${SOURCES}
)

add_dependencies(paltest_findnextfilew_test2 coreclrpal)

target_link_libraries(paltest_findnextfilew_test2
  ${COMMON_TEST_LIBRARIES}
)
