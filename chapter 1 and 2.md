[TOC]

**Anthropomatics** is the science of the symbioses between human and machine
**Why humanoids?** 

- Versatility 
- Better Prediction of robot actions
- Acceptance
- Building Humanoids = Building Human-Centred Technologies 

## Contact Detection and grasp verification

### Contact Detection using joint torques

- Compute weighted sum of finger joint torques
- Contact is detected where a threshold is surpassed.

### Object grasped successfully?

- Calculate distances:
  - between different  fingertips (for precision grasps)
  - between different fingertips and the palm (for power grasps)

## Detection of Deformability

###  Deformable objects can be detected:

- Grasp an object
- Verify that the grasp was successful
- Increase the joint torques
- Determine distances between the fingertips
  - Decreased distances indicate a deformable object

