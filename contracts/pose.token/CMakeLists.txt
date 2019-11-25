add_contract(pose.token pose.token ${CMAKE_CURRENT_SOURCE_DIR}/src/pose.token.cpp)

target_include_directories(pose.token
   PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR}/include)

set_target_properties(pose.token
   PROPERTIES
   RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}")
