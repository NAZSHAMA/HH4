# Module 1 — The Robotic Nervous System (ROS 2)

Goal:
Teach ROS 2 communication + humanoid robot control using Python and URDF.

Chapters:
1) ROS 2 Basics  
   - Nodes, Topics, Services  
   - Simple publisher/subscriber example

2) Python Control (rclpy)  
   - Control humanoid joints via Python  
   - Read sensor data

3) URDF for Humanoids  
   - Links + Joints  
   - Visualize robot model

Requirements:
- Include short explanations + diagrams + code samples
- Provide one hands-on task per chapter
- Content must be accurate and support chatbot retrieval

Outcome:
Students can control a basic humanoid and visualize its structure in ROS 2.

---

# Module 2 — The Digital Twin (Gazebo & Unity)

Goal:
Teach how humanoid robots are simulated through physics, environments, and sensors in Gazebo + Unity.

Chapters:
1) Physics Simulation in Gazebo
   - Gravity, collisions, environment setup
   - Spawn humanoid URDF into a world
   - Add sensors (LiDAR/Depth/IMU)

2) High-Fidelity Interaction in Unity
   - Import robot model and animate movement
   - Human-robot interaction visuals (camera, lighting)
   - Connect Unity with ROS 2 bridge

Requirements:
- Short explanations + diagrams + code samples
- One practical exercise per chapter (e.g., robot walking in simulated room)
- Only factual info aligned with tools used

Outcome:
Students can simulate a humanoid robot and interact visually with a digital twin.

---

# Module 3 — The AI-Robot Brain (NVIDIA Isaac)

Goal:
Teach advanced perception and navigation for humanoid robots using NVIDIA Isaac Sim, Isaac ROS, and Nav2.

Chapters:
1) Perception with Isaac Sim + Synthetic Data
   - Photorealistic environment
   - Generate labeled images for vision training
   - Simulate cameras for object detection

2) Navigation with Isaac ROS + Nav2
   - VSLAM for mapping and localization
   - Path planning for bipedal movement
   - Execute navigation commands from a Python agent

Requirements:
- Short explanations + minimal diagrams + code examples
- 1 practical task per chapter (e.g., detect object + walk to it)
- Stay accurate to NVIDIA Isaac tools

Outcome:
Students enable a humanoid to see, understand the environment, and navigate using AI.

---

# Module 4 — Vision-Language-Action (VLA)

Goal:
Show how LLMs and perception systems enable humanoid robots to follow natural language commands and act autonomously.

Chapters:
1) Voice-to-Action (Whisper + ROS 2)
   - Convert speech to text
   - Parse command into robot actions
   - Trigger ROS 2 movement and sensing tasks

2) Cognitive Planning with LLMs
   - Convert “Clean the room” into step-by-step actions
   - Integrate vision to identify targets
   - Execute actions in sequence on a simulated humanoid

Requirements:
- Brief explanations, diagrams, and minimal code
- 1 practical task per chapter (e.g., voice command → pick an object)
- Capstone alignment: full pipeline from voice input to successful manipulation

Outcome:
Students build a humanoid robot that understands language and performs real actions.
