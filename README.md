# Imepdance-project
This is a project design for Logan Liu's Lab project.
Credit to Chengpeng Hu, Kenny Ren and Xiangfei Zhou from University of Illinois at Urbana-Champaign.
The goal of the project is to use Mobile phone to sense the impedance of the DUT so that we can build a impedance sensing platform for various type of sensor.

The current source code is the third edition which can sense the resistance and temperature through an internal circuit with swtiches. 

You should consult Kenny's master thesis or Xiangfei Zhou to learn about how the hardware work.

Any software question should be directed to Chengpeng Hu. 

For the test impedance application on Android, it has two stages: 1. Calibration stage. 2. Sensing stage.

Whenever changing the peripheral settings, you should re-calibrate the internal parameters in the applicaiton. Repeated tests under same settings is not required to re-calibration since the parameters will be memorized by the application. 

If there is no previously calibrated parameters, the application will notify the user to first calibrate left channel as shown below.

<img src=https://github.com/WuhanMonkey/Test-Impedance/blob/master/CaliLeft.png width=400 height=700 />

Press Calibrate button will start calibrating the left channel. 

Then the application will prompt for right channel calibration as shown below.

<img src=https://github.com/WuhanMonkey/Test-Impedance/blob/master/caliRight.png width=400 height=700 />

Then, the system is ready for sensing as shown below. You can choose test resistance or test temperature depends on the switch position in hardware.

<img src=https://github.com/WuhanMonkey/Test-Impedance/blob/master/ready.png width=400 height=700 />

The most recent sensed result is shown as red in the estimated data. 

<img src=https://github.com/WuhanMonkey/Test-Impedance/blob/master/sense.png width=400 height=700 />


