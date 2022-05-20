cmake_minimum_required(VERSION 3.2)

project(raytracing-weekend CXX)

add_executable(raytrace export_ppm_image.cpp)
# .\001_export_ppm_image\cmake-build-debug\raytrace.exe > .\001_export_ppm_image\image.ppm
