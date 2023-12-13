set(component_srcs "esp_wifi.c")

idf_component_register(SRCS "${component_srcs}"
                       INCLUDE_DIRS "."
                       PRIV_INCLUDE_DIRS ""
                       PRIV_REQUIRES "wifi_provisioning" "nvs_flash"
                       REQUIRES "esp_nvs" )