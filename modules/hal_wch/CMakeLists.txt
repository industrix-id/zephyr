if(CONFIG_SOC_SERIES_QINGKE_V2A OR CONFIG_SOC_SERIES_QINGKE_V4C)
  zephyr_include_directories(${ZEPHYR_HAL_WCH_MODULE_DIR}/ch32v003fun .)
endif()
