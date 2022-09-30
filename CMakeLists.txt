

if(${CONFIG_STM32_XCUBEUSBPD})
    add_subdirectory (${CONFIG_SOC_SERIES}/STM32_USBPD_Library)
    zephyr_include_directories(${CONFIG_SOC_SERIES})
endif()

