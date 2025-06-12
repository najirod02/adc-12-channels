# ADC-12-channels
A simple project to read 12 analog signals and printing their digital values into UART.

## Pin used
We are using ADC2, in particular starting from channel IN0 to channels IN14 (excluding conflicting pins) which corresponds to:
- IN0 $\rightarrow$ PA0
- IN1 $\rightarrow$ PA1
- IN4 $\rightarrow$ PA4
- IN6 $\rightarrow$ PA6
- IN7 $\rightarrow$ PA7
- IN8 $\rightarrow$ PB0
- IN9 $\rightarrow$ PB1
- IN10 $\rightarrow$ PC0
- IN11 $\rightarrow$ PC1
- IN12 $\rightarrow$ PC2
- IN13 $\rightarrow$ PC3
- IN14 $\rightarrow$ PC4

## Shield pin
Starting from the left of the shield pinout:
- PIN 1 $\rightarrow$ IN12
- PIN 2 $\rightarrow$ IN13
- PIN 3 $\rightarrow$ IN0
- PIN 4 $\rightarrow$ IN1
- PIN 5 $\rightarrow$ IN4
- PIN 6 $\rightarrow$ IN8
- PIN 7 $\rightarrow$ IN11
- PIN 8 $\rightarrow$ IN10
- PIN 9 $\rightarrow$ IN7
- PIN 10 $\rightarrow$ IN6
- PIN 11 $\rightarrow$ IN14
- PIN 12 $\rightarrow$ IN9

## Board
The board used is the [Nucleo F446RE](https://os.mbed.com/platforms/ST-Nucleo-F446RE/).\
The following images show the pinout of the morpho headers.

<div align="center">
    <img src="https://os.mbed.com/media/uploads/jeromecoutant/nucleo_f446re_morpho_left_2021_10_26.png" width="600"/>
    <img src="https://os.mbed.com/media/uploads/jeromecoutant/nucleo_f446re_morpho_right_2021_10_26.png" width="600"/>
</div>