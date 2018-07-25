# Action Completion: A temporal model for Moment Detection

This repository contains the completion moment annotations for our BMVC 2018 paper.   
> Farnoosh Heidarivincheh, Majid Mirmehdi and Dima Damen,  
> Action Completion: A temporal model for Moment Detection,  
> In British Machine Vision Conference (BMVC), 2018.  

Paper available from [Arxiv](https://arxiv.org/abs/1805.06749).

When using these annotations, please cite:

> @INPROCEEDINGS{Heidarivincheh2018,
>    title={Action Completion: A temporal model for Moment Detection},
>    author={Heidarivincheh, Farnoosh and Mirmehdi, Majid and Damen, Dima},
>    booktitle={British Machine Vision Conference (BMVC)},
>    year={2018}
> } 
  
This folder includes completion moments of 16 actions from three datasets: HMDB [1], UCF101 [2], RGBD-AC [3].

In each file, lines contain \<videoName\> \<completionAnnotation\> \<train-test flag per split\>  

**train-test flags:**  
For HMDB and UCF101, the train-test flags match the original dataset splits. For RGBD-AC, they represent 'leave-one-person-out'.  
The train-test flags in each split are presented by numbers (1, 2 and 0) separated with '/'. Flag '1' shows the sequence is used for training, flag '2' shows the sequence is used for testing and flag '0' shows the sequence is not used for training and testing. For example, <1/2/0> means that in split 1 the sequence is used for training, in split 2 the sequence is used for testing and in split 3 the sequence is not used for training and testing.  

**completionAnnotation:**  
**Incomplete action sequences** have been annotated with 0.  
**Complete action sequences** have been annotated with the completion frame number, representing the moment that:  
  
*HMDB-catch*: the object is safely caught,  
*HMDB-drink*: the subject starts consuming beverage,  
*HMDB-pick*: the object is lifted off the surface,  
*HMDB-pour*: the liquid leaves the container and is poured,  
*HMDB-throw*: the object leaves the hand of the subject,  
  
*UCF101-basketball*: the ball goes through the hoop,  
*UCF101-blowing candles*: all the candles are blown out,  
*UCF101-frisbee catch*: Frisbee is safely caught,  
*UCF101-pole vault*: the subject clears the bar successfully,  
*UCF101-soccer penalty*: the ball crosses the goal line,  
  
*RGBD-AC-switch*: the room's illumination is changed,  
*RGBD-AC-plug*: the plug is safely positioned in the socket and the hand leaves it,  
*RGBD-AC-open*: the jar's lid is separated from the jar,  
*RGBD-AC-pull*: the drawer leaves its initial position and is pulled open,  
*RGBD-AC-pick*: the object is lifted off the surface,  
*RGBD-AC-drink*: the subject starts consuming beverage.  

The RGB frames can be obtained from:

For HMDB [1] and UCF101 [2] datasets: [https://github.com/feichtenhofer/twostreamfusion#data](https://github.com/feichtenhofer/twostreamfusion#data). 

For RGBD-AC [3] dataset: [RGBD-Action-Completion-2016 dataset](http://dx.doi.org/10.5523/bris.66qry08cv1fj1eunwxwob3fjz).  

References:

[1] H. Kuehne, H. Jhuang, E. Garrote, T. Poggio, and T. Serre. HMDB: a large video database for human motion recognition. In ICCV, 2011.

[2] K. Soomro, A. Roshan Zamir, and M. Shah. A dataset of 101 human actions classes from videos in the wild. arXiv preprint arXiv:1212.0402, 2012.

[3] F. Heidarivincheh, M. Mirmehdi, and D. Damen. Beyond action recognition: Action completion in RGB-D data. In BMVC, 2016.

If you have any question, please contact farnoosh.heidarivincheh@bristol.ac.uk
