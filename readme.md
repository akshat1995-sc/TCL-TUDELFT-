## Description
This project targets at identification and control of heater-sensor coupled system hosted on Arduino Leo. Multiple methods have been utilized
to identify the given system. This gray box modelling process included FODPT, SODPT and Physical Non-linear model. A brief discussion 
of the procedure used could be found in the file 'identification_summary.pdf'. The model which generalized best is later utilized to create a Model Predictive Controller with general step disturbance rejection. This controller could be found in the zip folder named *Tracking.rar*, within which, the file *heater_mpc.m* could be utilized to access the algorithm.

Note: "Final Video.mp4" features the real-time controller simulation. The last row has incorrect legends (actually supposed to be actuator magnitude in volts).
