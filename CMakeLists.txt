# Minimum CMake version required
cmake_minimum_required(VERSION 3.10)

# Project name and version
project(OfflineRenderer VERSION 1.0)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add source files
add_executable(OfflineRenderer src/main.cpp)

# Include directories
include_directories(include)

# Optional: Add libraries
# If you're using installed libraries like GLM or stb, no linking is needed since they're header-only.
