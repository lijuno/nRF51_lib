README
======


* This library uses PPI + GPIOTE tasks to generate PWM waves so that CPU is not needed except for parameter changing. 

* Based on the libraries from [this repository](https://github.com/NordicSemiconductor/nrf51-pwm-library). 

* Tested to work with (and without) SoftDevice 8.0.0.

* Added feature: 1) stop TIMER after disabling PWM to save power; 2) workaround for PWM frequency > 62.5 kHz (see discussion [here](https://devzone.nordicsemi.com/question/42518/random-pwm-dutycycle-inversion-in-softdevice-80/)). 