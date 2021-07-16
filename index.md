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

<iframe width="560" height="315" src="https://www.youtube.com/embed/l7XJVfmEx2k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

![image](https://user-images.githubusercontent.com/56204136/125957336-46de98be-b3d5-44ef-8c53-6709667d0dd0.png)


For my first milestone I finished building the robot arm, and also getting the servo motors working and using the potentiometers to move the motors. I connected each potentiometer to an analog pin so I could get an input for the motor. Servo values range from  0 to 180, but potentiometers range from 0 to 1023 so I needed to use the `map` function to scale down the input. Then I used the `Servo.write()` function to send the value to the servo and move it.

<img width="1093" alt="Screen Shot 2021-07-16 at 6 35 03 AM" src="https://user-images.githubusercontent.com/56204136/125956409-929ff43c-49bc-45cf-93aa-313e44062326.png">

Wiring:
 * Red wires: power
 * Black wires: ground
 * Green wires: GPIO pins

This is my curcuit. I had a total of 4 motors and potentiometers. Both had a similar design for their curcuits: a pin for power, a pin for ground, and a GPIO pin. The 5 volt pin on the arduino can't support 4 or more motors and I needed more power so I used a battery holder of 4 for 6.5V to power the servos. The potentiometers had a 3.3V power source. 



