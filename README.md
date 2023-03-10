# Servo-motor-angle-control-with-potantiometer---STM32F407
Servo motor control with PWM, potentiometer read with ADC

An analogue value is generated by the potentiometer. The value read from the potentiometer is proportioned according to the control range of the servo motor and PWM output is generated. The generated pwm signal is analysed with a logic analyser.

### SG90 Servo Motor:

<img src="https://github.com/CakirBrs/Servo-motor-angle-control-with-potantiometer---STM32F407/blob/main/Assets/sg90.jpeg" width="256" title="Servo motor pwm">

Contrary to what is written in the datasheet, the duty cyle control range is in the range of 0.5-2.5. 


## Microprocessor pin settings:

- A port pin 5 : Alternate function for PWM 

- A port pin 0  : Analog mode for potentiometer.  


<img src="https://github.com/CakirBrs/Servo-motor-angle-control-with-potantiometer---STM32F407/blob/main/Assets/servoBack.jpg" width="512" title="Servo motor pwm">


### Generated PWM signals:
![servopwm](https://user-images.githubusercontent.com/26774013/218906657-ff2215f7-5f1e-44d9-865b-cb08f106967f.gif)


### Video

https://user-images.githubusercontent.com/26774013/218906696-dba062ec-c258-49fc-9ff9-d935e70f7fac.mp4

