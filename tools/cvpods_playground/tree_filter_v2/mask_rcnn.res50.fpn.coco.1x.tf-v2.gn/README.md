# mask_rcnn.res50.fpn.coco.1x.tf-v2.gn  

seed: 33519520

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.409
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.616
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.444
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.241
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.440
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.541
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.327
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.518
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.544
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.360
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.576
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.685
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 40.946 | 61.569 | 44.448 | 24.138 | 43.962 | 54.075 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 54.319 | bicycle      | 31.254 | car            | 43.641 |  
| motorcycle    | 44.512 | airplane     | 64.296 | bus            | 63.313 |  
| train         | 62.408 | truck        | 34.422 | boat           | 27.870 |  
| traffic light | 28.490 | fire hydrant | 67.990 | stop sign      | 63.954 |  
| parking meter | 43.576 | bench        | 23.191 | bird           | 37.524 |  
| cat           | 64.387 | dog          | 59.974 | horse          | 56.574 |  
| sheep         | 54.377 | cow          | 54.619 | elephant       | 63.891 |  
| bear          | 67.807 | zebra        | 65.739 | giraffe        | 66.165 |  
| backpack      | 14.594 | umbrella     | 38.757 | handbag        | 13.808 |  
| tie           | 31.589 | suitcase     | 42.814 | frisbee        | 66.879 |  
| skis          | 22.337 | snowboard    | 32.830 | sports ball    | 48.228 |  
| kite          | 44.229 | baseball bat | 26.856 | baseball glove | 37.225 |  
| skateboard    | 50.750 | surfboard    | 39.464 | tennis racket  | 45.713 |  
| bottle        | 39.189 | wine glass   | 34.790 | cup            | 41.381 |  
| fork          | 33.059 | knife        | 17.782 | spoon          | 15.919 |  
| bowl          | 39.976 | banana       | 26.282 | apple          | 18.404 |  
| sandwich      | 31.999 | orange       | 30.369 | broccoli       | 22.509 |  
| carrot        | 23.928 | hot dog      | 33.960 | pizza          | 52.414 |  
| donut         | 46.783 | cake         | 37.218 | chair          | 27.009 |  
| couch         | 41.248 | potted plant | 25.829 | bed            | 45.104 |  
| dining table  | 27.920 | toilet       | 61.105 | tv             | 55.683 |  
| laptop        | 58.683 | mouse        | 64.210 | remote         | 30.823 |  
| keyboard      | 49.692 | cell phone   | 35.136 | microwave      | 56.854 |  
| oven          | 31.634 | toaster      | 31.483 | sink           | 37.626 |  
| refrigerator  | 54.330 | book         | 14.541 | clock          | 50.197 |  
| vase          | 39.358 | scissors     | 24.228 | teddy bear     | 44.283 |  
| hair drier    | 3.406  | toothbrush   | 18.976 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.370
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.585
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.395
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.181
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.391
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.541
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.305
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.472
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.494
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.305
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.524
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.648
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 36.965 | 58.459 | 39.508 | 18.074 | 39.070 | 54.147 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.567 | bicycle      | 17.481 | car            | 40.010 |  
| motorcycle    | 33.292 | airplane     | 51.972 | bus            | 63.244 |  
| train         | 60.991 | truck        | 34.175 | boat           | 22.684 |  
| traffic light | 27.247 | fire hydrant | 63.801 | stop sign      | 64.557 |  
| parking meter | 44.233 | bench        | 16.366 | bird           | 31.407 |  
| cat           | 65.328 | dog          | 56.650 | horse          | 39.904 |  
| sheep         | 47.359 | cow          | 45.814 | elephant       | 57.093 |  
| bear          | 65.882 | zebra        | 54.868 | giraffe        | 49.869 |  
| backpack      | 13.588 | umbrella     | 44.934 | handbag        | 14.184 |  
| tie           | 28.844 | suitcase     | 44.123 | frisbee        | 65.193 |  
| skis          | 2.830  | snowboard    | 21.286 | sports ball    | 48.814 |  
| kite          | 32.377 | baseball bat | 25.239 | baseball glove | 38.888 |  
| skateboard    | 29.486 | surfboard    | 31.537 | tennis racket  | 53.227 |  
| bottle        | 37.878 | wine glass   | 30.078 | cup            | 41.889 |  
| fork          | 15.117 | knife        | 11.636 | spoon          | 10.197 |  
| bowl          | 37.032 | banana       | 20.977 | apple          | 18.004 |  
| sandwich      | 33.320 | orange       | 29.598 | broccoli       | 21.208 |  
| carrot        | 20.713 | hot dog      | 25.787 | pizza          | 50.527 |  
| donut         | 47.842 | cake         | 36.985 | chair          | 17.808 |  
| couch         | 35.192 | potted plant | 22.096 | bed            | 35.498 |  
| dining table  | 16.299 | toilet       | 59.623 | tv             | 58.455 |  
| laptop        | 59.469 | mouse        | 63.395 | remote         | 29.074 |  
| keyboard      | 48.589 | cell phone   | 34.766 | microwave      | 58.643 |  
| oven          | 30.084 | toaster      | 33.812 | sink           | 35.017 |  
| refrigerator  | 55.635 | book         | 9.933  | clock          | 51.169 |  
| vase          | 38.437 | scissors     | 18.284 | teddy bear     | 43.144 |  
| hair drier    | 2.904  | toothbrush   | 15.731 |                |        |
