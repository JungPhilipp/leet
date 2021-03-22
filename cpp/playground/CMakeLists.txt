set(HEADERS
    include/playground.h
    )
set(SRC
    src/playground.cpp
    )


add_library(playground SHARED ${HEADERS} ${SRC})
target_include_directories(playground PUBLIC include)


add_subdirectory(tests)