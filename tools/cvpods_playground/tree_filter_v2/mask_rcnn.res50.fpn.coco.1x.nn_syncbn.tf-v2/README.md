# mask_rcnn.res50.fpn.coco.1x.nn_syncbn.tf-v2  

seed: 35583799

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.413
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.619
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.450
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.249
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.447
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.546
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.331
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.524
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.551
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.365
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.587
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.691
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 41.333 | 61.890 | 45.011 | 24.896 | 44.717 | 54.553 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 54.451 | bicycle      | 30.892 | car            | 43.305 |  
| motorcycle    | 42.913 | airplane     | 63.748 | bus            | 63.325 |  
| train         | 63.285 | truck        | 34.159 | boat           | 26.555 |  
| traffic light | 27.443 | fire hydrant | 68.047 | stop sign      | 63.681 |  
| parking meter | 46.278 | bench        | 24.508 | bird           | 37.142 |  
| cat           | 67.566 | dog          | 60.193 | horse          | 56.907 |  
| sheep         | 53.181 | cow          | 56.250 | elephant       | 62.721 |  
| bear          | 68.447 | zebra        | 65.916 | giraffe        | 64.365 |  
| backpack      | 13.938 | umbrella     | 39.051 | handbag        | 13.894 |  
| tie           | 33.040 | suitcase     | 41.010 | frisbee        | 66.730 |  
| skis          | 21.280 | snowboard    | 34.539 | sports ball    | 47.541 |  
| kite          | 44.596 | baseball bat | 29.331 | baseball glove | 37.475 |  
| skateboard    | 50.980 | surfboard    | 38.178 | tennis racket  | 45.434 |  
| bottle        | 39.193 | wine glass   | 36.468 | cup            | 41.922 |  
| fork          | 33.568 | knife        | 19.197 | spoon          | 16.963 |  
| bowl          | 40.034 | banana       | 24.128 | apple          | 21.653 |  
| sandwich      | 33.146 | orange       | 29.964 | broccoli       | 23.389 |  
| carrot        | 24.311 | hot dog      | 32.394 | pizza          | 50.693 |  
| donut         | 49.167 | cake         | 37.052 | chair          | 27.752 |  
| couch         | 39.132 | potted plant | 27.048 | bed            | 42.954 |  
| dining table  | 27.903 | toilet       | 61.473 | tv             | 55.724 |  
| laptop        | 59.924 | mouse        | 61.239 | remote         | 32.229 |  
| keyboard      | 49.832 | cell phone   | 33.941 | microwave      | 57.323 |  
| oven          | 32.751 | toaster      | 39.545 | sink           | 37.094 |  
| refrigerator  | 57.971 | book         | 15.833 | clock          | 50.793 |  
| vase          | 38.851 | scissors     | 28.033 | teddy bear     | 44.404 |  
| hair drier    | 5.475  | toothbrush   | 23.903 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.370
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.588
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.395
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.185
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.394
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.540
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.306
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.475
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.498
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.314
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.529
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.646
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 36.976 | 58.796 | 39.510 | 18.480 | 39.410 | 53.968 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.813 | bicycle      | 18.632 | car            | 40.128 |  
| motorcycle    | 32.282 | airplane     | 49.673 | bus            | 62.622 |  
| train         | 61.241 | truck        | 33.250 | boat           | 22.318 |  
| traffic light | 26.458 | fire hydrant | 62.676 | stop sign      | 64.277 |  
| parking meter | 46.781 | bench        | 17.716 | bird           | 31.275 |  
| cat           | 68.370 | dog          | 57.625 | horse          | 40.949 |  
| sheep         | 46.328 | cow          | 47.728 | elephant       | 56.828 |  
| bear          | 67.150 | zebra        | 55.942 | giraffe        | 47.575 |  
| backpack      | 13.474 | umbrella     | 45.340 | handbag        | 14.269 |  
| tie           | 30.518 | suitcase     | 41.812 | frisbee        | 64.616 |  
| skis          | 2.385  | snowboard    | 21.074 | sports ball    | 47.385 |  
| kite          | 31.863 | baseball bat | 24.364 | baseball glove | 38.503 |  
| skateboard    | 30.526 | surfboard    | 32.295 | tennis racket  | 52.621 |  
| bottle        | 37.745 | wine glass   | 32.213 | cup            | 42.099 |  
| fork          | 15.346 | knife        | 12.706 | spoon          | 11.641 |  
| bowl          | 37.456 | banana       | 18.562 | apple          | 20.971 |  
| sandwich      | 33.698 | orange       | 30.355 | broccoli       | 21.811 |  
| carrot        | 20.278 | hot dog      | 24.332 | pizza          | 49.730 |  
| donut         | 49.705 | cake         | 36.244 | chair          | 18.618 |  
| couch         | 32.517 | potted plant | 22.640 | bed            | 34.873 |  
| dining table  | 15.870 | toilet       | 58.495 | tv             | 57.197 |  
| laptop        | 59.696 | mouse        | 61.024 | remote         | 28.337 |  
| keyboard      | 48.337 | cell phone   | 32.147 | microwave      | 53.979 |  
| oven          | 30.133 | toaster      | 42.930 | sink           | 33.847 |  
| refrigerator  | 58.077 | book         | 10.605 | clock          | 52.224 |  
| vase          | 37.762 | scissors     | 19.961 | teddy bear     | 42.527 |  
| hair drier    | 1.004  | toothbrush   | 14.731 |                |        |
