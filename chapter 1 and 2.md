[TOC]

**Anthropomatics** is the science of the symbioses between human and machine
**Why humanoids?** 

- Versatility 

  - we need robots which are: versatile, i.e. can perform a wide variety of tasks
  - can act and interact in made-for-human environments
  - can use made for human robots

- Better Prediction of robot actions

  - motion behaviour of robots with human-like morphology, i.e. humanoid robots, allows humans to better predict the robot actions. This leads to intuitive and fluent human-robot interaction 

- Acceptance

  - human-like appearance may support and intuitive human-robot interaction but Uncanny Valley tells us something different!
  - Uncanny Valley:
    - The uncanny valley is the region of negative emotional response towards robots that seems 'almost' human. Movement amplifies the emotional response

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

