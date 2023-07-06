# TAPIR: Tracking Any Point with per-frame Initialization and temporal Refinement
Carl Doersch, Yi Yang, Mel Vecerik, Dilara Gokay, Ankush Gupta, Yusuf Aytar, Joao Carreira, Andrew Zisserman

## Summary
A model that effectively tracks any queried point on any physical surface throughout a video sequence. The approach employs two stages:
1. the matching stage- the model locates a suitable candidate point math for the query point on each frame.
2. refinement stage- updates both the trajectory and query features based on local correlations.
   
## Model and Concepts
