# CaltechCV Image Labeler

This is a small script to view and modify the labels in still images. 
It is adpated here specifically to view/modify the labels of lanes for 
the purpose of comparing performance of various algorithms.


There are two matlab scripts:
* ccvLabeler.m    - This is the viewer/editor of the labels
* ccvLabel.m      - This is the helping script to handle the labels data structure


Sample use:
```matlab
% This will open the viewer on clip cordova1
ccvLabeler('../cordova1/', 'labels.ccvl');
````

This specific version has been used to label the lanes in the [Caltech Lanes Dataset](http://www.mohamedaly.info/datasets/caltech-lanes/).

More information is available [here](http://www.mohamedaly.info/software/caltechcv-image-labeler).
