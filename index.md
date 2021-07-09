# Phone-Controlled Robot Arm
My project is a Robot Arm that can move in all directions and grab objects with it's claw. It uses the ESP32 to connect to a phone through bluetooth so the phone can control the Robot Arm. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Siddharth Maddikayala | American Highschool | CS/AI | Incoming Freshman

![IMG_0797](https://user-images.githubusercontent.com/56204136/125087642-80214880-e081-11eb-8c0c-bb2541abb60f.jpg)
  
# Final Milestone


# Second Milestone


<hr>
# First Milestone

For my first milestone I finished building the robot arm, and also getting the servo motors working and using the potentiometers to move the motors. I connected each potentiometer to an analog pin so I could get an input for the motor. Servo values range from  0 to 180, but potentiometers range from 0 to 1023 so I needed to use the `map` function to scale down the input. Then I used the `Servo.write()` function to send the value to the servo and move it.


