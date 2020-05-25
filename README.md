# smartPhoneAHRS
Attitude and Horizon Reference System (AHRS) application using Onboard smartphone Sensors
Linear Kalman Filter and Complementary Filter Attitude Estimation (AHRS) 
Using Onboard Smart Phone IMU 


Using this Simulink Model, you can use your smartphone sensors to get raw gyroscope, accelerometer, magnetometer data and estimate the real-time attitude of the phone using Kalman filter and Complementary. Pitch, Roll, Heading angles and rates.

This project is still in the development phase so use it at your own risk.
No noise filtering is done on the output. You can implement different noise reduction algorithms according to your application.

Because I don’t have an Apple development ID, I only uploaded the Android version. But you can easily just change the sensor inputs the iOS version from Simulink support Package for iOS device.


You need to have following items for building this project.
MATLAB 2019b or later / Simulink 10 or Later (because of using gauges in application you need 2019b or later)
Simulink support package for Android Device (or iOS if you wish)
Android Device equipped with Accelerometer , Magnetometer, Gyroscope (IMU)


A complete YouTube tutorial is available for this project in the following Link:
https://www.youtube.com/watch?v=NcLf0NCidj0



If you added a feature to this model, or fixed a bug please commit to this git project or send it to me.
I will update this project with better features in near future.

Let me know if you have a similar project or need help

E-mail: Ghaderi@alumsharif.org 
E-mail: p30planets@gmail.com 
WhatsApp: +989190123481 
Telegram: alireza787b
Instagram: Alireza787b



[![View Smart Phone AHRS on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/75798-smart-phone-ahrs)
