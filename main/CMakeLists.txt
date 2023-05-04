idf_component_register(SRCS "app_main.c" )

littlefs_create_partition_image(storage ../config_data)
