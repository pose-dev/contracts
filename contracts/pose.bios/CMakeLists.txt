add_contract(pose.bios pose.bios ${CMAKE_CURRENT_SOURCE_DIR}/src/pose.bios.cpp)

target_include_directories(pose.bios
   PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR}/include)

set_target_properties(pose.bios
   PROPERTIES
   RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}")
