cmake_minimum_required(VERSION 3.9 FATAL_ERROR)

project(PhysXBinaries C CXX)

install(
    DIRECTORY "${PROJECT_SOURCE_DIR}/include"
    DESTINATION ${CMAKE_INSTALL_PREFIX})

install(
    DIRECTORY "${PROJECT_SOURCE_DIR}/Windows"
    DESTINATION ${CMAKE_INSTALL_PREFIX})