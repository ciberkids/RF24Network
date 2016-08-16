

generate_arduino_library(RF24NetworkLib
        BOARD ${BOARD}
        SRCS RF24Network.cpp Sync.cpp
        HDRS RF24Network_config.h RF24Network.h Sync.h
        LIBS SPILib RF24Lib
        )
