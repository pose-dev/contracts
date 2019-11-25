cmake_minimum_required( VERSION 3.5 )

project(contracts)

set(EOSIO_WASM_OLD_BEHAVIOR "Off")
find_package(eosio.cdt)

add_subdirectory(pose.bios)
add_subdirectory(pose.msig)
add_subdirectory(pose.system)
add_subdirectory(pose.token)
add_subdirectory(pose.wrap)
