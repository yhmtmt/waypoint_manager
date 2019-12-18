add_library(waypoint_manager SHARED f_waypoint_manager.cpp)

target_include_directories(waypoint_manager PUBLIC ${PROJECT_SOURCE_DIR}/include)
install(TARGETS waypoint_manager DESTINATION lib)
