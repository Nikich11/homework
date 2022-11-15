cmake_minimum_required (VERSION 3.12)

project (hello_world)

add_executable (main
    main.cpp
    move_me_out.cpp
    move_me_out.h
    )

set_target_properties (hello_world PROPERTIES
    CXX_STANDARD 17
    CXX_STANDAR_REQUIRED ON
)