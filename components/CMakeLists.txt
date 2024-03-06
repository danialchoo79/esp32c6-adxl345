idf_component_register(SRCS "adxl345.c" "i2c.c"
                    REQUIRES driver
                    INCLUDE_DIRS "include")