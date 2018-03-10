cmake_minimum_required(VERSION 3.6 FATAL_ERROR)

add_executable(playground
    main.cpp
)

if (NOT ${MVSC})
    target_compile_options(playground
        PUBLIC
        -std=c++17
        PRIVATE
        -pendatic
        -Wall
        -Wextra
        -Werror
    )
endif (NOT ${MVSC})
