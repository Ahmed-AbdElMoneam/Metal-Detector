# Metal-Detector
Metal Detector is an application which can detect metal correctly by vibrating and produce (Metal is NEAR) message. It uses your smartphone Magnetometer (Magnetic Field Meter).
# Project Description
MetalDetector is an application which can be used in security procedures as It can detect metal correctly by vibrating and produce (Metal is NEAR) message. It uses your smartphone Magnetometer (Magnetic Field Meter) to measure the change of the Magnetic Field through the measured material. Due to this theory, If we find that the difference between metal and air magnetic field is large, we consider it as metal. In addition to the importance of this application in the security purposes, we can use it in something like Checking the Cooking utensils quality. Because If there is metal(iron) in the pot, it will rust soon. So, the presence of iron in pot is an evidence of the product high quality.
# Design
I have used two text views to display the sensor's output in a simple way. The first one will show the value output from the sensor in μTesla and the other will show the state if there is a metal near the sensor or not. I have adjusted the application to change the state from "Metal is AWAY" to "Metal is NEAR" when the value exceeds 55 μTesla in addition to vibration.
# Libraries & Hardware
Hardware: I have used Magnetometer to become the sensor.
Permission: I have used Vibrator to make vibrations.
Libraries: I have imported the sensor, text, hardware and etc. libraries.
