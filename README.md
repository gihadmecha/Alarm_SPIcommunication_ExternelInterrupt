# A Measurement Alarm System communicates using the SPI communication protocol and an EXI external interrupt.

[Demo](https://youtu.be/7MyPIFNfzwU?si=CCLDTq3jqmzXImPf) | [Proteus simulation file](https://github.com/gihadmecha/measurementAlarmSystem_SPIcommunication_ExternelInterrupt/blob/main/Alarm_SPIcommunication_ExternelInterrupt.pdsprj)
:-------------------------:|:-------------------------:
[![youtube2](https://github.com/gihadmecha/measurementAlarmSystem_SPIcommunication_ExternelInterrupt/assets/19871755/0a34612b-d039-48b0-98b5-6e025860fa11)](https://youtu.be/7MyPIFNfzwU?si=CCLDTq3jqmzXImPf) | ![proteus simulation2](https://github.com/gihadmecha/measurementAlarmSystem_SPIcommunication_ExternelInterrupt/assets/19871755/a01cdfe3-0fba-40a9-81e1-37f381382e92)

To measure the environment's temperature and detect smoke levels, enabling the timely activation of water sprinklers and alarms in response to a potential fire hazard.

The Measurement Alarm System (slave controller) gets the environment's temperature using a Temperature Sensor and puts it on the Display Screen.
- Normal State:
  - If temp < 45 °C
- Heat State:
  - If temp > 45 °C
  - The yellow light is on
- Fire State:
  - If temp > 45 °C and smoke level > 50
  - T
  - 
The Measurement Alarm System (slave controller) gets the environment's temperature using a Temperature Sensor and puts it on the Display Screen.

## Hardware
- two atmega32
- LM35 or potentiometer
- LCD 16x2
- Led
- BUZZER
- push button
- Resistors

## Peripherals
- SPI
- EXI
- ADC
- DIO

## Make sure you have installed
- [ATMEG32 MCAL layer](https://github.com/gihadmecha/Embedded_Systems/tree/main/atmega32_ECU/atmega32_ECU/MCAL).
- [HAL layer](https://github.com/gihadmecha/Embedded_Systems/tree/main/atmega32_ECU/atmega32_ECU/HAL).
- [Defined Data Types](https://github.com/gihadmecha/Embedded_Systems/blob/main/atmega32_ECU/atmega32_ECU/StdTypes.h).
- [atmega32 memory](https://github.com/gihadmecha/Embedded_Systems/blob/main/atmega32_ECU/atmega32_ECU/MemMap.h).
- [utilities](https://github.com/gihadmecha/Embedded_Systems/blob/main/atmega32_ECU/atmega32_ECU/UTILS.h).

## Softwares you should install
- Microchip Studio for AVR
- Proteus
