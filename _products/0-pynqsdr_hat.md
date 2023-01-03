---
name: PYNQSDR HAT
description_markdown: >-
  The add-on that brings openwifi to PYNQ-Z1 
description_markdown_full: |
  <br/>
  <b>One PYNQSDR HAT + PYNQ-Z1 ready-to-use combination for sale at 325$!</b><br/>
  <b>Few early debugging version for sale at 95$!</b><br/>
  The original idea from late 2021, now ready for sale. Even with a new 299$ PYNQ-Z1, this combo is still the cheapest available openwifi-capable platform(as of late 2022). <br/>
  Functions: PlutoSDR firmware, iio-oscilloscope, GQRX, dump1090, GNURadio, openwifi firmware, WiFi hotspot, packets capture, connect to other hotspots, and more. <br/>
  Why this: On usual ZYNQ + AD936X combinations, the two chips are tightly coupled on one board, making it hard if even possible to utilize the ZYNQ for general FPGA development. But here, with the extension removable, you still have a fully-functional PYNQ-Z1 ready for anything. So it's especially suitable for FPGA person who want to have a taste of SDR(like me), or vise versa. <br/>
  Limitations(or not): Due to bandwidth limitations of the TX PCB connections, 1RX1TX 40 MHz sample rate is the maximum. This is enough for all openwifi operations. This limitation can lifted by changing the series 200 Ohm resistors on PYNQ-Z1 PMOD to 0 Ohm. <b>If you buy the HAT + PYNQ-Z1 combo from here, I can do this modification for free and the full 61.44 MHz sample rate can be reached.</b> The baluns are not rated for 5 GHz, so transmission power is low. Also, I don't guarentee any exotic RF performance except that on my desk an iPhone can connect and communicate with the openwifi hotspot 20 cm away from the antennae.<br/>
  Items included: PYNQSDR HAT itself, HDMI cable x2, PMOD bridge x2, Antenna x2, SMA adapter x2. See picture below. <i>PYNQ-Z1 itself is NOT included!</i><br/>
  Connection: The 3 SMA connectors(2 used, one spare) on HAT are SMA-P(ordinary standard), the adapters are SMA-J to RP-SMA-P, the antennae are RP-SMA-J(WiFi standard). See picture below. <br/>
  Setup guide and software support(including pre-built ready-to-use SD card images): <a href="https://github.com/regymm/PYNQSDR">guide and more</a> / <a href="http://149.28.136.195/">prebuilt images</a> . <br/>
  ![](/regymm-toy-shop/images/products/pynqsdr_hat/1.jpg)
  ![](/regymm-toy-shop/images/products/pynqsdr_hat/2.jpg)

price: '125.00'
stock: 0
styles:
  - image: /images/products/pynqsdr_hat/0.jpg
---
