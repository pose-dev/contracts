add_contract(pose.msig pose.msig ${CMAKE_CURRENT_SOURCE_DIR}/src/pose.msig.cpp)

target_include_directories(pose.msig
   PUBLIC
   ${CMAKE_CURRENT_SOURCE_DIR}/include)

set_target_properties(pose.msig
   PROPERTIES
   RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}")
