cmake_minimum_required(VERSION 3.16)

project(MicMattMoe VERSION 1.0.0 LANGUAGES CXX)

add_executable(MicMattMoe src/MicMattMoe.cpp)
target_compile_features(MicMattMoe PRIVATE cxx_std_17)

if(MSVC)
    target_compile_options(MicMattMoe PRIVATE /W4)
else()
    target_compile_options(MicMattMoe PRIVATE -Wall -Wextra -Wpedantic)
endif()
