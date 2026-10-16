### Why SRAD DAQ?
Previous COTS DAQ systems had unreliable data saving mechanicsm that relied on connecting the DAQ to a laptop. This SRAD DAQ automatically stores the measured data to both a NAND Flash chip and a MicroSD card. Additionally this DAQ allows the PT sensor to be measured in parallel with other DAQ.

### Components
ESP32S3
TXS0108EPWR (Logic Level Shifter 3.3v <-> 5V)
ADS1115 (ADC)
74HC595D_118 (Shift register)
AMS1117 (3.3V LDO)

### Features
Measuring external 5V signal at 860sps via ADS1115
Measuring NTC Thermistors via ADS1115
5V I2C ports for Device communications (Adafruit Load Cell)
2x 3.3V UART ports for communications
8x LED status lights via shift register
