idf_component_register(SRCS "esp32_nat_router.c"
                            "portmap.c"
                            "dhcp_manager.c"
                            "vpn_manager.c"
                            "netif_hooks.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES esp_wifi esp_netif console nvs_flash driver esp_http_server fatfs dhcpserver wpa_supplicant esp_eth http_server json app_update cmd_router esp_app_format)
                    
