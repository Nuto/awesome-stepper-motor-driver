# Awesome stepper motor driver
An awesome list of stepper motor driver

## Motor driver

| Type | Step/Dir | SPI | UART | Motor Supply | Phase Current, RMS | Microsteps
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | -------------
| Trinamic TMC2100-LA | :white_check_mark: | :x: | :x: | 5 - 46V | 1.2A | 1...256
| Trinamic TMC2130-LA | :white_check_mark: | :white_check_mark: | :x: | 5 - 46V | 1.2A | 1...256
| Trinamic TMC2208-LA | :white_check_mark: | :x: | :white_check_mark: | 4.75 - 36V | 1.4A | 1...256
| Trinamic TMC2209-LA | :white_check_mark: | :x: | :white_check_mark:  | 4.75 - 29V | 2.0A | 1...256
| Trinamic TMC5160-TA | :white_check_mark: | :white_check_mark: | :white_check_mark: | 8 - 60V | 20.0A | 1...256
| Trinamic TMC5161-AA | :white_check_mark: | :white_check_mark: | :white_check_mark: | 8 - 40V | 3.5A | 1...256
| A4988 | :white_check_mark: | :x: | :x: | 8 - 35V | 2A | 1...16
| DRV8825 | :white_check_mark: | :x: | :x: | 8.2 - 45V | 2.2A | 1...32
| DRV8880 | :white_check_mark: | :x: | :x: | 6.5 - 45V | 2A | 1...16

## Stepper Motor

| Model | Voltage | Rated Current / Phase | Phase Resistance | Motor Type | Frame Size | Datasheet
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | -------------
| 17HS13-0404S | 12V | 0.4A | 30 Ω | Bipolar | NEMA 17 | https://www.oyostepper.com/images/upload/File/17HS13-0404S.pdf
| US-17HS4401S | 12V | 1.7A | 1.5 Ω | Bipolar | NEMA 17 | -

### Phase Resistance
Due more resistance, the motor will heat more. A higher resistance is therefore worse.

### Frame Size

| Frame Size | Size
| ------------- | -------------
| NEMA 6 | 14 x 14mm
| NEMA 8 | 20 x 20mm
| NEMA 11 | 28 x 28mm
| NEMA 14 | 35 x 35mm
| NEMA 16 | 39 x 39mm
| NEMA 17 | 42 x 42mm
| NEMA 23 | 57 x 57mm
| NEMA 24 | 60 x 60mm
| NEMA 34 | 86 x 86mm
| NEMA 42 | 110 x 110mm

### Cable Connector

| Type | Connection
| ------------- | -------------
| HX2.54 6pin | Motor
| DuPont 4pin | Motor driver (default)
| HX2.54 4pin | Motor driver

## Some Links

https://www.allaboutcircuits.com/tools/stepper-motor-calculator/
https://howtomechatronics.com/tutorials/arduino/how-to-control-stepper-motor-with-a4988-driver-and-arduino/
