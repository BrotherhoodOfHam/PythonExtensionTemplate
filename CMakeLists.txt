cmake_minimum_required(VERSION 3.8)

project(PythonExtensionTemplate)

add_subdirectory("${PROJECT_SOURCE_DIR}/pybind")

pybind11_add_module(
    template
    template/template.cpp
)
