idf_component_register(SRCS "main.c"
                            "iothub.c"
                        INCLUDE_DIRS "." "/usr/local/include/azureiot/"
                        "/home/dan/src/azure-iot-sdk-c/deps/umock-c/inc/"                                       "/home/dan/src/azure-iot-sdk-c/deps/azure-macro-utils-c/inc/"
                        PRIV_REQUIRES nvs_flash readtemp)


component_compile_definitions(SET_TRUSTED_CERT_IN_SAMPLES)
