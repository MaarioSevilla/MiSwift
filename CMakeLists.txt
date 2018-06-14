cmake_minimum_required(VERSION 3.10)
project(MiSwift)

add_custom_target(MiSwift ALL
        COMMAND /usr/bin/swift build
        WORKING_DIRECTORY ${CMAKE_SOURCE_DIR}
        SOURCES Sources/main.swift)
