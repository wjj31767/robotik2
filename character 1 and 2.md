**Anthropomatics** is the science of the symbioses between human and machine
**Why humanoids?** 

- Versatility 
- Better Prediction of robot actions
- Acceptance
- Building Humanoids = Building Human-Centred Technologies 

---

### Master Motor Map

#### Goal: 

- offer an unified representation of bodies models to design humanoid robots
- Reference model of the human body
  - for humanoid robot design
  - Imitation of human actions
  - Action recognition
  - Visualization of human movements
- *Interfaces and data structures* for the *transfer of motor knowledge* between different embodiments

#### Models:

1. **Kinematic model**: joints and segment lengths
   - Kinematic model of the human shoulder-arm system: 
     - 9 DOF 
     - Shoulder: 5 DOF
     - Elbow: 2 DOF 
     - Wrist: 2 DOF
2. **Dynamic model**: segment mass, center of mass and moments of inertia
3. **Statistic/anthropomorphic model**: Segment properties(e.g. length, mass etc.) defined as a function(regression) of global parameters(e.g. body height, weight)

#### Motion reproduction using MMM:

- Data from stereo based markerless human motion capture system
- Data from VICON system(SFB 588)

#### How to use MMM:

Replacement of any module(perception, recognition, visualization, reproduction) can be guaranteed by using the MMM as the exchange format

 - All perceptive modules convert their output to the MMM format
 - All recognition and reproduction modules convert the MMM format to their specific internal representation

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

