add_library(waypoint_manager SHARED f_waypoint_manager.cpp ${CHANS})

target_include_directories(waypoint_manager PUBLIC ${PROJECT_SOURCE_DIR}/include)
target_include_directories(waypoint_manager PUBLIC ${PROJECT_SOURCE_DIR}/channels)

install(TARGETS waypoint_manager DESTINATION lib)
