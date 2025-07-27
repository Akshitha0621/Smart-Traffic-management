# Smart Traffic Management
## This repo contains simulation code of  Smart traffic management system

### 🚦 Intelligent Traffic Signal Simulation using Pygame

This is a Python-based simulation of a smart traffic signal system at a four-way intersection. It adjusts the green signal time dynamically based on vehicle density to optimize traffic flow.

---

#### 📸 Demo

![Simulation Screenshot](https://github.com/Akshitha0621/Smart-Traffic-management/blob/eca7da95b974a0598872a6f6a5275480888e7b6f/images/intersection.jpg) <!-- Add a screenshot if you have one -->

---

##### 📁 Project Structure
traffic-signal-simulation/

├── simulation.py
                               
├── README.md  

├── requirements.txt 

├── images/ 

│   ├── mod_int.png 

│   ├── signals/

│   │   ├── red.png

│   │   ├── yellow.png

│   │   └── green.png

│   ├── right/  

│   │   ├── car.png

│   │   ├── bus.png

│   │   ├── truck.png

│   │   ├── bike.png

│   │   └── rickshaw.png

│   ├── left/   

│   │   ├── car.png

│   │   ├── bus.png

│   │   ├── truck.png

│   │   ├── bike.png

│   │   └── rickshaw.png

│   ├── up/   

│   │   ├── car.png

│   │   ├── bus.png

│   │   ├── truck.png

│   │   ├── bike.png

│   │   └── rickshaw.png

│   └── down/    

│       ├── car.png

│       ├── bus.png

│       ├── truck.png

│       ├── bike.png

│       └── rickshaw.png

└── demo/

    └── demo.png     
   

---

###### 🚀 Features

- Simulates traffic from 4 directions: up, down, left, right
- Supports 5 vehicle types: car, bus, truck, rickshaw, bike
- Vehicles can turn at intersections
- Adaptive green light timing based on vehicle count
- Real-time visualization using Pygame
- Signal countdown and vehicle pass count display

---

###### 🛠️ Requirements

- Python 3.7+
- Pygame


---


#### ⚙️ How It Works

- Vehicles are generated randomly in different lanes and directions.

- The green signal is dynamically assigned based on a weighted count of     vehicle types.

- Vehicles move, stop at signals, and turn when needed.

- The simulation displays the traffic flow in real-time.

---
##### ⚙️ Traffic Signal Logic

- Default Red: 150 sec

- Green: 20 sec (adaptive)
  
- Yellow: 5 sec
  
- Adaptive green time is calculated based on the number of vehicles waiting.

---
#### 📈 Output

- Console shows real-time updates of signal status.

- Pygame window shows:

- Vehicles moving through the intersection

Traffic light color transitions

- Countdown timers and vehicle counts

##### LICENSE

This project is licensed under the [MIT License](LICENSE).

