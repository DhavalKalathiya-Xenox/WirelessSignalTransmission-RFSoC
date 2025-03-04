# WirelessSignalTransmission-RFSoC
Wireless Signal Transmission and LED Control Using RFSoC-PYNQ in JupyterLab.
## Hardware Requirements
- Zynq UltraScale+ RFSoC boards (Transmitter and Receiver)
- Antennas connected to DAC/ADC
- PMOD circuit with transistors and RGB LEDs for external LED control
- 12V Power supply and Ethernet cables

## Software Requirements
- PYNQ framework (preloaded on RFSoC)
- Python libraries: numpy, ipywidgets, time, ...
- JupyterLab interface (accessed via board IP)

## How to Use
1. Clone this repository
2. Copy the `src/` files into your RFSoC JupyterLab environment
3. Run `transmitter_code.py` on the transmitter board
4. Run `receiver_code.py` on the receiver board
5. Press the on-board buttons to transmit different frequencies

## License
(If you choose a license, mention it here, e.g. MIT License, Apache 2.0, etc.)

## Contact
For questions, contact [Your Name] at [Your Email].
