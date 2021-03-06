# Spectacle-for-blind
This is spectacle that helps a blind person to walk in the road. The spectacle contains three Maxbotix EZ0 ultrasonic sensors. Two of them situated in the spectacle and the rest of the one is situated in the tactile finger ring. There are three vibrating motors (used in cell phone) which objective to alert the blind person through vibration. When any obstacle is detected in the ground or left or right then they begin to vibrate so the blind person awares about the obstacle position and can avoid that direction of walking.   


## Platform
### Hardware Module
* Arduino Mega2560

### Language
* C++

## System Components
### Sensors
* Ultrasonic sensors (Maxbotix EZ0)

### Alerting Vibrators
* Simple vibrating motor (Used in Cell Phone)

## Implementation
### Interfacing Peripherals
At first two ultrasonic sensors are mounted in the left and right side of the spectacle and the last one is mounted in the finger ring. The three vibrators are mounted in that three places. And they are interfaced in a Arduino Mega2560 board.

### Complete Circuit Diagram
![alt tag](https://github.com/TanveerKUET/Spectacle-for-blind/blob/master/BlindSpectacle%20Circuit%20Diagram.jpg) 

## System Requirement
* 9V DC battery

## Performance Analysis
For performance test I measured distance from several floors such Concrete and Tiles and then compared to the actual distance. The performance is shown in the figure.

![alt tag](https://github.com/TanveerKUET/Spectacle-for-blind/blob/master/performanceSpectacle.png)


