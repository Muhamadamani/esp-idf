if(IDF_TARGET STREQUAL "esp32")
    idf_component_register(SRC_DIRS "."
                    PRIV_INCLUDE_DIRS "."
                    PRIV_REQUIRES cmock test_utils)
endif()

