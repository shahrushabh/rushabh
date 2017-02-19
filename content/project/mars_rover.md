+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Mars Rover"

# Project summary to display on homepage.
summary = "iRobot navigation on artificial maze."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "marsrover/boundary.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["embedded_systems"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = "My caption :smile:"

+++

Mars Rover is an embedded system projects, that exposes students to embedded programming. Making use of C programming language along with the VORTEX platform, "that includes iRobot Create, the Cerebot II board, and attachments such as servo, SONAR, IR sensor, and LCD" panel. Teams, group of 3-4, are asked to calibrate sensors and program the robot for different tasks, one at a time. For example, Moving and turning the robot accurately, receiving and sending messages using serial communication, calibration of various sensors, and so on. The final project demonstration depends on the accuracy with which data is being fetched and analyzed. Demo required students to navigate the robot to the destination, without looking at the course, by analysis of data, in real time, received from the robot's sensors.

### Goal
Every team is given 10 minutes to navigate their robot through the maze and find the destination, determined by the supervising TA. Teams get penalized for hitting one of the obstacles or going out of bounds, or falling into the trap. Going over the time limit is also subject to penalty.

### Responsibility
My team included a group of 4 people; myself and one CprE major, one Com S major and one EE student. Having different major created some misunderstanding occasionally, but everything worked out at the end with hard work. Through:

* Calibration of iRobot's sensors, including Sonar sensor, IR sensor, Servo.
* Serial Data transmission for sending commands and receiving data.
* With curiosity and eager to learn, I took an extra step to implement the matlab GUI and communication logic between the robot and computer which served as very useful component during our program execution.
* Plot and update the graph with the most recent data received from the iRobot.
