cmake_minimum_required(VERSION 3.5)

idf_component_register(
                       SRCS "WiFiManager.cpp"
                       INCLUDE_DIRS "."
                       PRIV_REQUIRES arduino-esp32
)

project(WiFiManager)
