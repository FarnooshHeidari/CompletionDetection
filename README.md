# Completion Moment Annotations  
We present the annotations for completion moments of 16 actions from three datasets: HMDB, UCF101, RGBD-AC.  
  
**Complete action sequences** have been annotated with the completion frame number, representing the moment that:  
  
*HMDB-catch*: the object is safely caught,  
*HMDB-drink*:  the subject starts drinking,  
*HMDB-pick*: the object is lifted off the surface,  
*HMDB-pour*: the subject starts pouring,  
*HMDB-throw*: the object is observed thrown.  
  
*UCF101-basketball*: the ball goes through the hoop,  
*UCF101-blowing candles*:  all the candles are blown out,  
*UCF101-frisbee catch*: Frisbee is safely caught,  
*UCF101-pole vault*: the subject jumps over the bar successfully,  
*UCF101-soccer penalty*: the ball passes the goal line.  
  
*RGBD-AC-switch*: the room's illumination is changed,  
*RGBD-AC-plug*:  the plug is observed in the socket,  
*RGBD-AC-open*: the lid is observed off the jar,  
*RGBD-AC-pull*: the drawer is pulled open,  
*RGBD-AC-pick*: the object is lifted off the surface,  
*RGBD-AC-drink*: the subject starts drinking.  
  
  
**Incomplete action sequences** have been annotated with 0.  
Sequences not used for trian/test have been annotated with -1.  

For HMDB and UCF101 datasets, we have used RGB frames available at [https://github.com/feichtenhofer/twostreamfusion](https://github.com/feichtenhofer/twostreamfusion). For RGBD-AC, we have used RGB frames available at [RGBD-Action-Completion-2016 dataset](http://dx.doi.org/10.5523/bris.66qry08cv1fj1eunwxwob3fjz).  

For more details please read our paper in [here](https://arxiv.org/abs/1805.06749).
