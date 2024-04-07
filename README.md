# SliderHO

This is an opensource slider for marco photography 
Currently using Swift for the IOS app and runs on an esp32s3 T-Display amoled fron Liligo with Arduino.
The Adruino environment seems to be limited so it will move to C and C++ sooner or later.

The Rail :
 1x Stepper motor nema 17
 2x MGN12C rails 150mm
 1x T8 Pitch 2mm Lead 8mm, 150mm (plan to test 4, 2, 1 mm lead) gives a resolution up to 0.0014 mm
 1x 3D Printed railbed
 1x 3D prited sledge (Alu machined sledge in the making)

 The Controller :
  1x Liligo ESP32S3 T-Display AMOLED
  1x TMC 5160 Stepper driver module (BigtreeTech) (Plan to test TMC2240 ) 
  1x stepdown converter 32v to 3.3v
  1x LiPo 2s, 3s, 4s, (7v to 32v for stepper motor and driver)

 Software :
  Arduino code for the esp32S3 module 
  Xcode SwiftUI Project

FreeDAC Project for the printed parts.

As soon I have verified the function of every thing I will comiit it here. 

