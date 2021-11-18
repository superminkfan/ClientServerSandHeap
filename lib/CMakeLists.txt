add_executable(test "")

target_link_libraries(test PRIVATE ${Boost_LIBRARIES})
target_sources(test PRIVATE
    src/serverClientTest.cpp )
