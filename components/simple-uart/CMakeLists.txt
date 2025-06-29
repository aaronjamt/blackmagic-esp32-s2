idf_component_register(SRCS "simple-uart.c"
                    INCLUDE_DIRS "."
                    REQUIRES esp_driver_gpio esp_hw_support driver)
