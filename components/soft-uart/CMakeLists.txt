idf_component_register(SRCS "soft-uart.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES esp_hw_support
                    REQUIRES esp_driver_gpio driver)