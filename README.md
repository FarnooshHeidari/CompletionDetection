# Annotations for Completion Moment Detection
We present the annotations for completion moments of 16 actions from three datasets.  
  
**Complete action sequences** have been annotated with the completion frame number, representing the moment that:  
  
**HMDB** (HMDB_completion_moment_annotations.txt)  
*catch*: the object is safely caught,  
*drink*:  the subject starts drinking,  
*pick*: the object is lifted off the surface,  
*pour*: the subject starts pouring,  
*throw*: the object is observed being thrown.  

**UCF101** (UCF101_completion_moment_annotations.txt)  
*basketball*: the ball goes through the hoop,  
*blowing candles*:  all the candles are blown out,  
*frisbee catch*: Frisbee is safely caught,  
*pole vault*: the subject jumps over the bar successfully,  
*soccer penalty*: the ball passes the goal line.  

**RGBD-AC** (RGBD-AC_completion_moment_annotations.txt)  
*switch*: the room's illumination is changed,  
*plug*:  the plug is observed in the socket,  
*open*: the lid is observed off the jar,  
*pull*: the drawer is pulled open,  
*pick*: the object is lifted off the surface,
*drink*: the subject starts drinking.  
  
  
**Incomplete action sequences** have been annotated with 0.  
Sequences not used for trian/test have been annotated with -1.  

For HMDB and UCF101 datasets, we have used RGB frames available at [https://github.com/feichtenhofer/twostreamfusion](https://github.com/feichtenhofer/twostreamfusion). For RGBD-AC, we have used RGB frames available at [RGBD-Action-Completion-2016 dataset](http://dx.doi.org/10.5523/bris.66qry08cv1fj1eunwxwob3fjz).  

For more details please read our paper in [here](https://arxiv.org/abs/1805.06749).
