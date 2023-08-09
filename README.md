# Taiko Vibrator

This is an adult toy driving circuit that make an egg vibrator vibrate according to the fumen of Yuugen no Ran.

# How to manufacture

1. Zip the files in pcb/fab and submit it to jlc.com. It should cost at most 20 CNY. Old JLC users have chances to get PCBs for free.
2. Buy the components according to pcb/bom.csv.
  - Alternatively, you can buy additionally 2 pieces of 1x16 2.54mm connector socket in case you need to swap the Arduino Nano.
  - BE CAREFUL ABOUT THE DIRECTION OF THE USB PORT OTHERWISE THE NANO WOULD BURN!
3. Solder the components onto the PCB.
4. Buy a USB-powered egg vibrator from taobao.com. This should cost less than 20 CNY.
5. Disassemble the vibrator (you may need to de-solder), and screw two poles of an egg into the output socket.
6. Use Arduino IDE to program `mcu-code/taiko_vibrator.ino` onto the Arduino Nano.
7. Power the whole thing with the USB socket on the top-right, ideally with a portable USB power source.

# Final product
![Photo of final product](/images/vibrator.jpg)