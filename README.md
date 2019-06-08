## Training data for learning the activity intention model of the elderly
```description01
   This repository contains dataset to build the activity intention model of the elderly. 
   This data was collected by performing a project of MSIP/IITP. 
   If you have any questions or comments, please feel free to contact us by email [phkchr09@gmail.com].
```

## Data overview
```description02
   In this project, the activity intention model was learned based on 55 types of actions, 10 types of poses 
   and 4 types of IoT sensor information. Therefore, this data was represented by sequences to compose of 
   action, pose, IoT sensor values and activity intention. 
```

## Data format
 ```description03
   This data is represented by a sequence of the following format.
   Time, Pose, Action, bd, ld, bm, lm, activity_intention 
   * bd - bathroom_door_status
   * ld - livingroom_door_status
   * bm - motion_status in bathroom
   * lm - motion_status in livingroom
   ```
 
## Details of data
 * [Actions of the elderly (55 types)](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/Action/README.md)
 * [Poses of the elderly (10 types)](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/Pose/README.md)
 * [IoT sensor values (door/motion)](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/IoT/README.md)
 * [Activity intentions](https://github.com/ssu0221/AIR_TrainingDataSet/blob/master/data_description/Activity_Intention/README.md)

## The institute to construct dataset
 * __Action, pose and IoT data collection : KETI(Korea Electronics Technology Institute)__
 * __Activity intention labeling: The AI Lab in Soongsil University__


## Citation
If our dataset is helpful, please kindly cite the following paper:
 ```description04
 @INPROCEEDINGS{
  kimESWA19,
  title={An approach  for recognition of human’s daily living patterns using intention ontology and event calculus},
  author={Kim, Jemin and Jeon, Myungjoong and Park, Hyunkyu and Bea, Seokhyun and Bang, Sunghyuk and Park, Youngtack},
  booktitle={Journal of Expert Systems with Applications (ESWA)},
  year={2019}
}
 ```

## Acknowledgement
 * This work was supported by the ICT R&D program of MSIP/IITP. [2017-0-00162, Development of Human-care Robot Technology for Aging Society]
 
 
 
 

