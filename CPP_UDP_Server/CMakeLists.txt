﻿# CMakeList.txt : CMake project for CPP_UDP_Server, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (CPP_UDP_Server "main.cpp"  "Source/udp_server.cpp" "Source/udp_server.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET CPP_UDP_Server PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
