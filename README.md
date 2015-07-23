# OVAproject

Key words: Optics, Arduino Pro Mini, ADS1105,ADC,PWM,CoolTerm,UART...

This is a project in which an optical variable attenuator is driven and controlled by arduino pro mini

The microcontroller is ATmega328p, which is installed on the arduino pro mini. Besides, the load is a optical variable 
attenuator (OVA-650), whose attenuation is propotional to the output of a potentialmeter or voltage divider. The OVA
is driven by the PWMs generated by the arduino, and the value of potentialmeter' voltage is read by ADS1105, a 12-bit
ADC component. The arduino will request to obtain the voltage from ADS1105 and receive the result through I2C. Moreover,
Cool Term on PC is used to communicate with the arduino, and in other words, the user can send commands to the arduino
through this interface.

The project is in progress, and we are very happy to share our codes with you and willing to hear any comments ,suggestions
and advice from you.

By the way, thanks the "Information Technology" in 21st century that provide me with abundant resources to refer to.

More details will be published on the website: http://youqian2012.github.io/OVAproject
