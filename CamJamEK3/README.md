# CamJamEK3

Java API to control a CamJam EduKit 3 – Robotics (http://camjam.me/?page_id=1035).

All the component use the PI4J library (http://pi4j.com/) except for the HCSR04 ultrasound sensor that use a native library build base on the Wiring Pi library ( http://wiringpi.com/ )


## Build the project
Before building the subproject locally you have to build the parent one. Refer to the PiRobotPlatform readme file for instructions.
Then you can build and run the program with mvn install and mvn antrun:run

Runnable examples in the examplesCJEK3 package:
* LineSingleIRSensorExample.java
* MotorsExample.java
* UltrasoundSensorExample

You can run each one in the artifacts directory using the command "sudo java -cp file.jar class". For example:

    sudo java -cp Pi2Go-0.0.1-SNAPSHOT-jar-with-dependencies.jar examplesCJEK3.LineSingleIRSensorExample


**** Running the examples will make your robot move with all the possible consequences. ****



## Terms and conditions:

This software is provided as is. No responsibility of any kind is taken by the author.
Although the author has tried all the softwares on his computers he does not guarantee that they work on your environment and that they are safe for you to use.

*** Use at your own risk!! ***

All the trademarks are properties of their owner.
This author is not related in any way to any entity (corporation, person, brand, trademark, …) mentioned in this page.

## Many thanks for their work to:
All the people that developed the projects quoted in this page. I learned a lot from their work and also get many part and idea.
Expecially for the Maven pom files I have to thank the people of the Pi4J projects.
I hope I have respected all the licenses terms and conditions. Otherwise, let me know, and I will comply with their requirements.
