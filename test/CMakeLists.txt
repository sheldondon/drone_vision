

add_executable ( rtp_test rtp_test/rtp_test.c )

target_include_directories ( rtp_test PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/cv)
target_include_directories ( rtp_test PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/test/arch/linux)

target_link_libraries ( rtp_test LINK_PUBLIC DroneVision )
