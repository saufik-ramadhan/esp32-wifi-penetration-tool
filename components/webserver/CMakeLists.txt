idf_component_register(SRCS "webserver.c"
                    INCLUDE_DIRS "interface"
                    PRIV_REQUIRES esp_event hccapx_serializer pcap_serializer esp_http_server wifi_controller main)