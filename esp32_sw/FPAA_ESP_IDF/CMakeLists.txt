cmake_minimum_required(VERSION 3.16.0)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(FPAA_ESP_IDF)
spiffs_create_partition_image(spiffs ../data FLASH_IN_PROJECT)
