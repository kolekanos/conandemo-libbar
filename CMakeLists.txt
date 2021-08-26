cmake_minimum_required(VERSION 3.20)
project(Bar
    VERSION 0.1.0
    DESCRIPTION "Simple C library"
    HOMEPAGE_URL "https://example.com"
    LANGUAGES C
)

include(GNUInstallDirs)

set(CMAKE_FIND_PACKAGE_PREFER_CONFIG ON)
list(APPEND CMAKE_PREFIX_PATH "${CMAKE_BINARY_DIR}")

add_subdirectory(source)

