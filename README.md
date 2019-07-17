# E-Grasping: Robotic Grasping Detectionwith Event-based Camera andEvent-Stream Dataset
a Grasping DataSet Captured by DVS (Dynamic vision sensor)

# Overview
This is the implementation of our recently work 'E-Grasping: Robotic Grasping Detectionwith Event-based Camera andEvent-Stream Dataset'. 
We construct a robotic grasping dataset name E-Grapsing with100  objects.  For  each  object,  there  are4020successive  grasping  annotations  in  different  views  with  atime resolution of1ms. A spatio-temporal mixed particle filter is proposed to track the LED-based grasprectangles which enables video-level annotation of a single grasp rectangle per object. As LEDs blink at highfrequency, the E-Grapsing dataset is annotated in a high frequency of 1 kHz. The original arxiv paper can be found here. The final version will be updated after publication process.

If you find it helpful for your research, please consider citing:

If you encounter any questions, please contact me at GuangChen[at]tum[dot]de[dot]edu


![image](https://github.com/HuCaoFighting/DVS-GraspingDataSet/blob/master/images/sampleeventrgb.jpg)
# DataSets
# Single Grasp DataSets
we represent the tracked LED points with rectangles,each event frame acquires the ground truth of a good grasping position , as is shown in below


![image](https://github.com/HuCaoFighting/DVS-GraspingDataSet/blob/master/images/single_posi.png)

# Multi-Grasp DataSets
  we  manually  set  ground  truth  annotations  in  the  firstframe,  the  transformed  annotations  in  any  other  frame  canbe attained.The final dataset with multi-graspingannotations is illustrated in below
  
  
 ![image](https://github.com/HuCaoFighting/DVS-GraspingDataSet/blob/master/images/multi_posi.png)
