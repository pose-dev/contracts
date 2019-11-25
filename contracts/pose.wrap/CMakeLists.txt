add_contract(pose.wrap pose.wrap ${CMAKE_CURRENT_SOURCE_DIR}/src/pose.wrap.cpp)

target_include_directories(pose.wrap
   PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR}/include)

set_target_properties(pose.wrap
   PROPERTIES
   RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}")
