# Autonomous Truck Simulator
Author: Erik Börve, borerik@chalmers.se  

 ## Purpose
 This project provides an implementation of an autonomous truck in a multi-lane highway scenario. The controller utilizes non linear optimal control to compute and optimze over a set of feasible paths.

 ## Getting Started

 ### Prerequisites

 Clone the project in your local machine.

Locate the repo and run:
* pip
  ```sh
  pip install -r requirements.txt
  ```


## Usage
Simulations are run via the "main" file. This is also where simulations are configured, including e.g., designing traffic scenarios and setting up the optimal controllers.

 ## Project Structure
The projects contains the following files.
```bash
.
├── controllers.py
├── gitignore
├── helpers.py
├── main.py
├── README.md
├── requirements.txt
├── scenarios.py
├── simRes.gif
├── templateRLagent.py
├── traffic.py
└── vehicleModelGarage.py

```

 ### controllers.py
 makeController:
 Generates Model predictive controller based on specified scenario
 decisionMaster:
 Optimizes the trajectory choice, returns optimal policy.
 ### helpers.py
 Contains assisting functions, e.g., for data extraction and plotting
 ### main.py
 ### requirements.txt
 ### scenarios.py
 ### templateRLagent.py
 ### traffic.py
 ### vehicleModelGarage.py
