# Create a library called "influxdb_client_zynq"
add_library(influxdb_client_zynq_lib influxdb_client_zynq.cpp)

# Specify include directories for the library
target_include_directories(influxdb_client_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
