zephyr_include_directories("${CMAKE_CURRENT_LIST_DIR}/../cJSON")
zephyr_library()
zephyr_library_sources(
    "${CMAKE_CURRENT_LIST_DIR}/../cJSON/cJSON.c"
    "${CMAKE_CURRENT_LIST_DIR}/../cJSON/cJSON_Utils.c"
)
