//WiFi Car (ESP32-CAM Rover)//
//Live Video • Web Control • Remote Navigation//

//Overview:
-->A WiFi-controlled robotic rover with live video streaming, designed to explore remote or unsafe environments.
-->The project demonstrates embedded networking, real-time streaming, and motor control using a single ESP32-CAM module.

//Features:
-->Live camera feed via browser
-->Web-based control dashboard
-->Forward / Back / Left / Right motion
-->Compact and low-cost rover design

//Hardware Used:
-->ESP32-CAM
-->L298N Motor Driver
-->DC Motors & Chassis
-->Battery Pack

//Software Stack

-->Arduino framework
-->ESP32 Web Server
-->HTML/CSS/JS-based control panel

//System Architecture
-->ESP32-CAM hosts a local web server
-->User connects via WiFi
-->Commands sent via browser buttons
-->Motor driver executes movement
-->Camera stream provides visual feedback

//Why This Project Matters
Demonstrates:
-->Real-time human–machine interaction
-->Multi-domain integration (networking + robotics)

//Limitations & Challenges
-->Limited FPS due to ESP32-CAM constraints
-->WiFi range dependent on environment
-->No autonomous navigation (manual control)

//Key Learnings
-->ESP32-CAM can handle both vision and control
-->Power management is critical in mobile robots
-->Simple systems can still deliver strong functionality

//Future Improvements
-->Obstacle avoidance
-->Autonomous navigation modes
-->Cloud-based video relay
