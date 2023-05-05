# mqtt_stm32
This repository show a very simple example of how run MQTT, LWIP and FreeRTOS to publish data to a local network Mosquitto Server
# Hardware Requirements
NUCLEO-F767Zi

# Software requirements
STM32CubeIDE Version: 1.12.1
Embedded Software Package: STM32F7 1.17.0
Mosquitto Server running in a local network

#Example specifications
The firmware was set with a fixed local IP. You need to change based in your local network parameters
The example will public a message every second to te topic "test"
This example run in a FreeRTOS enviroment. Look for the task function

This example is only for demostration and maybe can contain bad practices or any issue.
For direct contact send me a message: carlos1992@hotmail.es
