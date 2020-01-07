# Imitation Learning

learning from human observation

- Imitation is an advanced behaviour whereby an individual observes and replicates another's behaviour.

## different viewpoints of Imitation learning

- Computer science 
  - Three Phases Model
    [Screenshot-2020-01-07-at-10-47-52.png](https://postimg.cc/XrTLLT4k)
    - Decomposition into subproblems
    - Solution to different problems
    - Integration of the solution
- Cognitive science
  focus on "software" of brains
   - ~~c5 s6~~
   - true imitation, if 
     - the imitated behaviour is absolutely new for the imitator 
     - the same strategy is employed as that of the demonstrator
     - the same task goal is achieved
     - ~~c5 s7~~
   - from today's view, imitation is also an important expression of higher intelligence
   - Innate Releasing Mechanism(IRM)
     - Every newborn has a certain repertoire of innate movement patterns
     - Be observing others' movements, these pattern will be activated and a correspondent movement is released
     - The model is very interesting because it supports the idea of implementing a **set of pre-programmed behaviours** in a technical system(robot) to bootstrap learning by imitation
     - IRM is unlikely because
       - many movements can be imitated, which means that a large number of these movements should be pre-programmed
       - newborns are constantly trying to **improve the imitated movements** which also speaks against a firm anchorage
   - Active Intermodal Mapping(AIM) Modell: 
     - The visual perception of the teacher's movement is converted into a higher level representation that can be matched against appropriately transformed proprioceptive information about one's own movement
     - if this match space is given, imitation can be seen as **learning to achieve a target representation**, a problem can be tackled with techniques from supervised learning
- Neuroscience and Cognitive Neuroscience
  Focus on "Hardware" of brains
   - Imitations-region in brains(F5)
   - Active during observation **and** movement
   - Active during **whole** observation
