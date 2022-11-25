cmake_minimum_required(VERSION 3.23)
project(TestClipper)

set(CMAKE_CXX_STANDARD 17)

add_executable(Test_1 main.cpp clipper.core.h clipper.engine.h
        clipper.export.h clipper.h clipper.minkowski.h
        clipper.offset.h clipper.rectclip.h
        clipper.engine.cpp clipper.offset.cpp clipper.rectclip.cpp
        )
