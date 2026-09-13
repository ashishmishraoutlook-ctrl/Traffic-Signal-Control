**Adaptive Traffic Signal Control System using Learning Agent**




Overview


This project simulates an intelligent traffic signal control system that dynamically adjusts green signal timing based on traffic density. Unlike traditional fixed-time signals, this system adapts to changing traffic conditions using a simple learning agent approach.





Problem Statement

Traffic congestion is a common issue in urban areas. Conventional traffic signals operate on fixed timings, which often leads to inefficient traffic flow. There is a need for a system that can respond dynamically to real-time traffic conditions and optimize signal timing.






Proposed Solution

The system monitors the number of vehicles at a given time and classifies traffic into:
•	High Traffic
•	Medium Traffic
•	Low Traffic



Based on this classification:

•	Signal time increases during high traffic

•	Signal time decreases during low traffic

Additionally, a reward-based mechanism evaluates whether the adjustment was effective, allowing the system to behave like a learning agent.



<img width="456" height="173" alt="image" src="https://github.com/user-attachments/assets/caeee207-09ba-4b1f-980d-6d192eb8f0d1" />







Technologies Used

•	Python – Core programming language
•	Pandas – Data handling and simulation
•	Matplotlib – Visualization of traffic patterns


How to Run the Project

1.	Install required libraries:
pip install -r requirements.txt
2.	Run the main program:
python main.py






Output


•	Console-based simulation of traffic signals

•	Dynamic adjustment of signal timing

•	Identification of peak and low traffic hours

•	Graph showing how signal timing adapts over time




<img width="427" height="233" alt="image" src="https://github.com/user-attachments/assets/33bf1d8f-aa92-4363-9ab9-b490401e9f70" />








Learning Approach

This project implements a simple learning agent:

•	Observes traffic (input)

•	Takes action (adjusts signal time)

•	Receives feedback (reward/penalty)

•	Stores experience for analysis

This mimics basic principles of reinforcement learning.





Future Enhancements

•	Integration with real-time traffic data (IoT sensors/APIs)

•	Implementation of advanced reinforcement learning algorithms (Q-learning)

•	Development of a graphical user interface (GUI)

•	Multi-intersection traffic management system







Learning Outcomes

•	Understanding of intelligent agent systems

•	Application of basic machine learning concepts

•	Data analysis and visualization

•	Real-world problem-solving using Python


BY
Ashish Mishra

