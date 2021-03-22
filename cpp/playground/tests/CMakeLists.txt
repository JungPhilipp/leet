set(TEST_HEADERS
    )
set(TEST_SRC
    main.cpp
    )

add_executable(playground_test ${TEST_HEADERS} ${TEST_SRC})
target_link_libraries(playground_test PRIVATE playground doctest)
add_test(playground_test playground_test)