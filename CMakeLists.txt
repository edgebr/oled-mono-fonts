# Copyright (c) 2025, Centro de Inovação Edge.
# SPDX-License-Identifier: BSD-3-Clause

if(CONFIG_OLED_FONTS)
    zephyr_library()
    zephyr_library_sources(src/fonts.c)
    zephyr_include_directories(includes)
endif ()
