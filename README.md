PLATFORMIO BOARDFILE GENERATOR
==============================

This super simple script was written to generate platformio boardfiles for STM32G0.

The source is a excel spreadsheet directly from ST's Website.
Just visit https://www.st.com/en/microcontrollers-microprocessors/stm32g0-series.html#
Click on "Product selector" and then "Export".

In addition to jupyter, you need `pandas`, `jinja2` and `xlrd` (for excel import).