# Crossing Realities: Connecting the Virtual and the Physical World for Remote Inspections

Daphne Barretto, Manuel Kreutle, Alex Glaser

*Abstract.* Nuclear disarmament is the only solution to the threat of a global nuclear war. Traditional verification approaches of nuclear arms-control agreements have placed a strong emphasis on onsite inspections. Considering the large numbers of U.S. and Russian warheads as well as situations of political tensions or restricted global travel, in-person onsite inspections require a significant amount of time, resources, and trust between parties. Virtual or remote inspections could facilitate and accelerate the disarmament process. While prior work has discussed how virtual reality could potentially be used for training and capacity-building in nuclear disarmament verification, in this work, we extend this idea and explore the possibility of combining virtual and in-person activities to reduce the intrusiveness and cost of inspections. Our approach discusses the use of bidirectional data flows and interaction between the inspector’s virtual environment and the host’s dismantlement facility. We implement a full virtual-reality environment and a physical demonstration to explore the technology and challenges of inspections conducted in virtual reality. For one direction of data flow we use fiducial markers to algorithmically estimate the location and orientation of a warhead, a robot, and other relevant elements of the physical world via an RGB camera, provide the pose estimation data to a virtual reality project in Unreal Engine 5, and use 3D models of the tracked objects to show their relative positions in an immersive virtual reality environment with real-time updates. This provides inspectors in virtual reality with the key information from the physical world. For the other direction of data flow we develop code to control a programmable robot from the virtual reality environment so that it moves in the physical world. This provides inspectors with a way to interact with the physical world even though they are not physically present, as e.g. a radiation detector or other sensors could be mounted on the robot. Combined, this work discusses and demonstrates how virtual reality and robotics could be used for nuclear disarmament.

# Technology

This work utilizes ArUCO Markers for pose estimation, an iRobot Create 3 and its corresponding SDK, and Unreal Engine 5 for virtual reality development.

# Acknowledgements

This work utilizes the [ArUCo-Markers-Pose-Estimation-Generation-Python](https://github.com/GSNCodes/ArUCo-Markers-Pose-Estimation-Generation-Python) for pose estimation with ArUCO Markers and [the Python SDK for iRobot Edu robots](https://github.com/iRobotEducation/irobot-edu-python-sdk).
