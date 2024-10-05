# Include the WebUI headers
include_directories(${CMAKE_SOURCE_DIR}/include)

# Define the executable target
add_executable(my_webui_project main.cpp)

# Link the WebUI library
target_link_libraries(my_webui_project ${CMAKE_SOURCE_DIR}/lib/libwebui-2-static.a)