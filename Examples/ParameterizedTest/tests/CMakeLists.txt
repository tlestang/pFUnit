cmake_minimum_required(VERSION 3.12)
project(xcompact3d LANGUAGES Fortran)

find_package(PFUNIT REQUIRED)
enable_testing()
add_pfunit_ctest(tests TEST_SOURCES Test_Cases.pf)

