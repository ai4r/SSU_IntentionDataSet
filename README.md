## Training data for learning the activity intention model of the elderly
```description01
   This repository contains dataset to build the activity intention model of the elderly. 
   This data was collected by performing a project of MSIP/IITP. 
   If you have any questions or comments, please feel free to contact us by email [phkchr09@gmail.com].
```

### Data overview
```description02
   In this project, the activity intention model was learned based on 55 types of actions, 10 types of poses 
   and 4 types of IoT sensor information. Therefore, this data was represented by sequences to compose of 
   action, pose, IoT sensor values and activity intention. 
```

### Data format
 ```description03
   This data is represented by a sequence of the following format.
   Time, Pose, Action, bd, ld, bm, lm, activity_intention 
   * bd - bathroom_door_status
   * ld - livingroom_door_status
   * bm - motion_status in bathroom
   * lm - motion_status in livingroom
   ```
 
### Details of data
 * [Actions of the elderly (55 types)](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/Action/README.md)
 * [Poses of the elderly (10 types)](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/Pose/README.md)
 * [IoT sensor values (door/motion)](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/IoT/README.md)
 * [Activity intentions](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/Activity_Intention/README.md)

### The institute to construct dataset
 * __Action, pose and IoT data collection : KETI(Korea Electronics Technology Institute)__
 * __Activity intention labeling: The AI Lab in Soongsil University__

### Citation
If our dataset is helpful, please kindly cite the following paper:
 ```description04
 @INPROCEEDINGS{
  yoonICRA19,
  title={Robots Learn Social Skills: End-to-End Learning of Co-Speech Gesture Generation for Humanoid Robots},
  author={Yoon, Youngwoo and Ko, Woo-Ri and Jang, Minsu and Lee, Jaeyeon and Kim, Jaehong and Lee, Geehyuk},
  booktitle={Proc. of The International Conference in Robotics and Automation (ICRA)},
  year={2019}
}
 ```



### 본 데이터가 적용된 논문
 * [An approach for recognition of human’s daily living patterns using intention ontology and event calculus (Expert Systems with Applications, 2019)](https://www.sciencedirect.com/science/article/pii/S0957417419302349?via%3Dihub)
 
 
 
 

