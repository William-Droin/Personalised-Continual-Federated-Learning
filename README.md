# Personalised Continual Federated Learning
Continual learning for personalised federated Learning

#### -- Project Status: [In Developement]

## Introduction
The purpose of this project is to offer a new way to do Personalised Federated Learning by utilising continual learning and model clustering.
This is part of a 3rd year personal research project at the University of Exeter.

## Visual Explanation
This new approach is divided in 3 different phases
### Phase 1
A centralised server distributes a general models on the devices:

<img src="https://user-images.githubusercontent.com/72973649/196041230-94538f80-d7a3-4994-bafc-df60feb0308e.png" width="300">

### Phase 2
Models continually train on local data

<img src="https://user-images.githubusercontent.com/72973649/196043243-523860ed-c63b-431a-8566-0859d9732658.png" width="300">

### Phase 3
Models are sent back to the server to be analysed and compared

<img src="https://user-images.githubusercontent.com/72973649/196043437-ee0b5dc8-7489-4c63-8978-25e0ef319123.png" width="300">

### Phase 4
Devices are divide into clusters based on the similarities of their models. 
There is no longer a single general model being distributed to all devices like in traditional federated learning, instead, there is a one general model per cluster and devices only share their knowledge with devices from the same cluster. 
New devices are going through phase 1 again before being assigned to a cluster.

<img src="https://user-images.githubusercontent.com/72973649/196045030-b7de07b7-8097-4568-b60f-b81c59aa8665.png" width="400">
