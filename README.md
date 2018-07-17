# Completion Moment Detection
We present the annotations for completion moments of 16 actions from three datasets as follows:  
  
**HMDB** -> HMDB_completion_moment_annotations.txt  
*catch*: When the object is safely caught, *drink*:  When the subject starts drinking, *pick*: When the object is lifted off the surface, *pour*: When the subject starts pouring, *throw*: When the object is observed being thrown.  

**UCF101** -> UCF101_completion_moment_annotations.txt  
**RGBD-AC** -> RGBD-AC_completion_moment_annotations.txt  

These annotations are subjective and defined based on application.
  
**Complete actions** have been annotated with the completion frame number.  
**Incomplete actions** have been annotated with 0.  
Sequences not used for trian/test have been annotated with -1.  

We have used RGB frames of HMDB and UCF101 available at [https://github.com/feichtenhofer/twostreamfusion](https://github.com/feichtenhofer/twostreamfusion) and RGBD-AC at [RGBD-Action-Completion-2016 dataset](http://dx.doi.org/10.5523/bris.66qry08cv1fj1eunwxwob3fjz).  

For more details please read our paper in [here](https://arxiv.org/abs/1805.06749).
