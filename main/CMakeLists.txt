idf_component_register(SRCS "ntp.c" "main.c" "wifi.c" "udp.c" "ntp.c"
                    PRIV_REQUIRES esp_wifi nvs_flash
                    INCLUDE_DIRS "."
                    REQUIRES esp_driver_gpio
                    )

