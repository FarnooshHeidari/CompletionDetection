# Completion Moment Detection
We present the annotations for completion moments of 16 actions from three datasets as follows:  
  
**HMDB** (HMDB_completion_moment_annotations.txt) The completion moments represent the moment that,  
*catch*: the object is safely caught, *drink*:  the subject starts drinking, *pick*: the object is lifted off the surface, *pour*: the subject starts pouring, *throw*: the object is observed being thrown.  

**UCF101** (UCF101_completion_moment_annotations.txt) The completion moments represent the moment that,  
*basketball*: the ball goes through the hoop,  
*blowing candles*:  all the candles are blown out,  
*frisbee catch*: Frisbee is safely caught,  
*pole vault*: the subject jumps over the bar successfully,  
*soccer penalty*: the ball passes the goal line.  

**RGBD-AC** (RGBD-AC_completion_moment_annotations.txt) The completion moments represent the moment that,  
*switch*: the light is switched off,  
*plug*:  the plug is observed in the socket,  
*open*: the lid is observed off the jar,  
*pull*: the drawer is pulled successfully,  
*pick*: the object is lifted off the surface,
*drink*: the subject starts drinking.  
  
**Complete actions** have been annotated with the completion frame number.  
**Incomplete actions** have been annotated with 0.  
Sequences not used for trian/test have been annotated with -1.  

We have used RGB frames of HMDB and UCF101 available at [https://github.com/feichtenhofer/twostreamfusion](https://github.com/feichtenhofer/twostreamfusion) and RGBD-AC at [RGBD-Action-Completion-2016 dataset](http://dx.doi.org/10.5523/bris.66qry08cv1fj1eunwxwob3fjz).  

For more details please read our paper in [here](https://arxiv.org/abs/1805.06749).
