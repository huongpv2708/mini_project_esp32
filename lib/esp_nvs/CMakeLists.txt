set(component_srcs "esp_nvs.c")

idf_component_register(SRCS "${component_srcs}"
                       INCLUDE_DIRS "."
                       PRIV_INCLUDE_DIRS ""
                       PRIV_REQUIRES "nvs_flash"
                       REQUIRES "" )