# Event-based Robotic Grasping Detection with Neuromorphic Vision Sensor and Event-Grasping Dataset
A Grasping DataSet Captured by DVS (Dynamic vision sensor)

# Overview
This is the implementation of our recently work 'Event-Based Robotic Grasping Detection With Neuromorphic Vision Sensor and Event-Grasping Dataset'(https://www.frontiersin.org/articles/10.3389/fnbot.2020.00051/full). 
We construct a robotic grasping dataset name E-Grapsing with 91 objects. The dataset can be donwload from this link(https://drive.google.com/file/d/1frAvxFjjhBzhhNd2SeDKN1R6E417jD3L/view?usp=sharing)

If you find it helpful for your research, please cite:

```bibtex
@ARTICLE{10.3389/fnbot.2020.00051,
  
AUTHOR={Li, Bin and Cao, Hu and Qu, Zhongnan and Hu, Yingbai and Wang, Zhenke and Liang, Zichen},   
	 
TITLE={Event-Based Robotic Grasping Detection With Neuromorphic Vision Sensor and Event-Grasping Dataset},      
	
JOURNAL={Frontiers in Neurorobotics},      
	
VOLUME={14},      

PAGES={51},     
	
YEAR={2020},      
	  
URL={https://www.frontiersin.org/article/10.3389/fnbot.2020.00051},       
	
DOI={10.3389/fnbot.2020.00051},      
	
ISSN={1662-5218},   
}
```

![image](https://github.com/HuCaoFighting/DVS-GraspingDataSet/blob/master/images/sampleeventrgb.jpg)
# DataSets
# Single Grasp DataSets
We represent the tracked LED points with rectangles, each event frame acquires the ground truth of a good grasping position, as is shown in below


![image](https://github.com/HuCaoFighting/DVS-GraspingDataSet/blob/master/images/single_posi.png)

# Multi-Grasp DataSets
We manually set ground truth annotations in the first frame, the transformed annotations in any other frame canbe attained. The final dataset with multi-grasping annotations is illustrated in below
  
  
 ![image](https://github.com/HuCaoFighting/DVS-GraspingDataSet/blob/master/images/multi_posi.png)
