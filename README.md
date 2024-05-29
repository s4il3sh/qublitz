# QuBlitz Virtual Qubit Simulator
Welcome! 
## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)
## Overview 
Qublitz is a simulation tool aimed to lower the barrier to entry for students in high school and college trying to learn about Quantum Engineering. All simulations on Qublitz demonstrate the behavior of a single, two level qubit that occupies states between 1 and 0. Qublitz contains several simulation environments: Free Play, Gates Challenge, Step Pulse Challenge, Custom Qubit Query and Neutral Atoms. The engine behind every mode in Qublits is `quantum_simulator.py` which takes in given parameters to simulate the behavior of a single, two level qubit. 

### Free Play Mode
Free play mode is a sandbox contained in the `1_free_play_mode.py` page and grants users access to most parameters necessary to simulate any qubit behavior they want to. There are two simulation modes in Free Play, the time domain and frequency domain. 
In the time domain, the user can determine both the qubit's properties and send a micorwave square pulse to see how it reacts in the Bloch sphere and graphs of the expected probability of the bit being in the 1 state. 
In the frequency domain, the user can observe the responsiveness of a qubit to a range of different driving frequencies (frequency of the pulses we influence the qubit with).

### Gates Challenge [UNITARY HACK ISSUE]
The Gates Challange in the `2_gates_challenge.py` page is, unlike free play mode, a directed game that follows a story structure with a tutorial and challenges for the user that get progressively more difficult. The challenges are focused on helping the user practice navigating along the bloch sphere using X and Y gates. 

### Step Pulse Challenge [UNITARY HACK ISSUE] 
The Step Pulse Challenge in the `3_step_pulse_challenge.py` page is also a directed game that follows a story structure with a tutotial and challneges. Unlike the Gates Challenge, these are focused on helping the user create gates using microwave pulses. 

## Installation 
### Libraries
Qublitz will initially be hosted as a Streamlit app. The relevant libraries for installation are as follows: 
`streamlit`
`pandas`
`numpy`
`plotly.graph_objects`
`plotly.subplots`
`plotly.express`
each page will also need to import `run_quantum_simulation` from `quantum_simulator`
for the quantum simulator you will need to import `qutip`

## Usage
Find the current website here:
https://qublitz-qubit-lab.streamlit.app/
[![Unitary Fund](https://img.shields.io/badge/Supported%20By-UNITARY%20FUND-brightgreen.svg?style=for-the-badge)](https://unitary.fund)

## Contributing 
### General Steps 
To start contributing, fork the repository and clone the fork so you can run your version of Qublitz locally. Then, create a new branch `git checkout -b feature-branch-name` name the branch based on the feature you are working on. Eg. `git checkout -b gates-challenge`. Once your changes are made, commit them and push to branch. Finally open the pull request. 
### Specific Projects 
For the Gates Challenge, you should take the existing `2_gates_challenge.py` page and modify it. You may rewrite all of the code if you like but the gates page contains starter code for displaying the Bloch Sphere and showing how X and Y-Gates work. 
For the Step Pulse Challenge, you should take the existing `3_gates_challenge.py` page and modify it.  You may rewrite all of the code if you like but the gates page contains starter code for displaying the Bloch Sphere and input for creating a Step Pulse. 

## Contact 
For help or advice email: 
neo.y.cai.25@dartmouth.edu 
mattias.w.fitzpatrick@dartmouth.edu

