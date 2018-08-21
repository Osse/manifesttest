cmake_minimum_required(VERSION 3.10)

project(Manifesttest)

add_executable(${PROJECT_NAME}
    main.cpp
    Manifesttest.exe.manifest
)
