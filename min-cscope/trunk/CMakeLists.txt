CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
SET(CMAKE_VERBOSE_MAKEFILE ON)

PROJECT(min-cscope)

IF(NOT CMAKE_BUILD_TYPE)
    SET(CMAKE_BUILD_TYPE Release)
ENDIF(NOT CMAKE_BUILD_TYPE)

MESSAGE("Build type is set to ${CMAKE_BUILD_TYPE}")

ADD_SUBDIRECTORY(sort)
ADD_SUBDIRECTORY(src)
