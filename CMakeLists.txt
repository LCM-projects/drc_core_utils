cmake_minimum_required(VERSION 2.6.0)

# pull in the pods macros. See cmake/pods.cmake for documentation
set(POD_NAME drc_core_utils)
include(cmake/pods.cmake)

add_subdirectory(src/drc_utils)
#add_subdirectory(src/bot_frames_cpp)
#add_subdirectory(src/gtkmm-renderer)
#add_subdirectory(src/joint_utils)
add_subdirectory(src/simple_lcm_bridge)
