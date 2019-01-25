# STMicroelectronics

These examples demonstrate how to use the Simulink Coder Support Package for STMicroelectronics Nucleo Boards to run a Simulink® model on an STMicroelectronics Nucleo board.

Simulink Coder Support Package for STMicroelectronics Nucleo Boards enables you to create and run Simulink models on supported STMicroelectronics Nucleo boards. The support package includes a library of Simulink blocks for configuring and accessing STMicroelectronics Nucleo peripherals and communication interfaces.

In this example you will learn how to configure a simple Simulink model to generate code for STMicroelectronics Nucleo F103RBT6 board and run the generated code on the board to periodically turn an LED on and off. You can configure this model for other supported Nucleo boards by browsing to >>Configuration Parameters >>Hardware Implementation >>Hardware board and selecting the required board.

## Prerequisites

1-)- If you are new to Simulink, we recommend completing the Interactive Simulink Tutorial.\
2-)- If you are new to Simulink Coder, visit the Embedded Coder product page for an overview and tutorials.\
3-)- If you have not yet installed ST-Link/V2 USB drivers, follow the steps as described in Install Drivers for STMicroelectronics Nucleo boards.

## Required Hardware

To run this example you shall need the following hardware :

1-)- Supported STMicroelectronics Nucleo boards.\
2-)- USB type A to Mini-B cable.

![model](https://user-images.githubusercontent.com/43390471/51721641-928e9f80-204a-11e9-943c-0c9b5a9bfee5.png)

## Configure Model for Code Generation and Deploy into hardware board

In this task, you will configure a simple model to run on the STMicroelectronics Nucleo board.

1. Open the STM32F103_Nucleo_64_Blinking_LED.slx model. This model has been configured for the Nucleo F103RB board. Follow the steps shown in the figure below to configure the model for the appropriate Nucleo board:

![02](https://user-images.githubusercontent.com/43390471/51721689-bbaf3000-204a-11e9-9d31-8507e591b5e5.png)







