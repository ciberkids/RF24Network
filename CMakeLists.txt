

generate_arduino_library(RF24NetworkLib
        BOARD nano
        SRCS RF24Network.cpp
        HDRS RF24Network_config.h RF24Network.h
        LIBS RF24Lib
        )
