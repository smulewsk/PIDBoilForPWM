# PID Logic with boil threshold controlling GPIO PWM.

If the target temperature is above a configurable threshold the PID will be ignored and heater is switched on constantly.
Additionally, when measured temperature is above boil temperature the power is reduced to configurable value.


## Parameter

* P - proportional value
* I - integral value
* D - derivative value
* max power - Max power for PID and during ramp-up
* PID threshold - Temperature for PID threshold
* boil power - Power value in boil mode
* boil temperature - When  reached this boil temperature kettle power is changed to boil power
* sample time - Speed of the PID controller
