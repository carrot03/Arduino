## Content
This project demonstrates the usage of the Sound sensor to light up the LED if the detected sound is higher than the set threshold value. The detected value when the LED is on, is displayed on the LCD screen. [Fritzing project](./sound-sensor.fzz)

## [Live Demo](./assets/sound-sensor-video.mp4)


[**Serial Plotter Demo**](./assets/sound-sensor-serial-plotter.mp4)


## How it works
When the detected analog data read by the AOUT is higher than the set threshold value, the LED goes on and the value shows up on the LCD screen. 
The potentiometer (referred to **Trim-pot Adjust Sensitivity** in image 1) is used for increasing the increment. It sets up the threshold value for digital output of the sensor. 

## Components:
- 1x Arduino Mega2560
- 1x Sound Sensor STM32
- 1x breadboard
- 2x 220 OHM Resistors
- 1x LED
- 1x Potentiometer
- 3x F-M wires
- 21x M-M wires


## Set up
<img src="./assets/setup.jpg" width="50%" hight="50%"> 

## Wiring Diagram
<img src="./assets/sound-sensor_bb.png" width="50%" hight="50%">

## Circuit Schematic
<img src="./assets/sound-sensor_schem.png" width="50%" hight="50%">


</br>

| PINOUT | VALUE |     DESCRIPTION     |
|--------|-------|---------------------| 
| VCC    | 3.3v  |     Power input     |
| GND    |  GND  |       Ground        |
| AOUT   | ----  | Analog data output  |
| DOUT   | ----  | Digital data output |

**Table 1**: Description of the PINOUTs of the STM32 Sound Sensor 

| The working frequency range of the sound sensor is **50Hz ~ 20KHz**.


<img src="./assets/Sound-Sensor-Module-Parts.jpg" width="50%" hight="50%"> 

**Image 1:** Sound Sensor Module Parts. [source](https://circuitdigest.com/microcontroller-projects/interfacing-sound-sensor-with-arduino)
</br>

<img src="./assets/Sound-Sensor-Module-Pinout.jpg" width="50%" hight="50%"> 

**Image 2:** Sound Sensor Module PINOUT. [source](https://circuitdigest.com/microcontroller-projects/interfacing-sound-sensor-with-arduino)
</br>