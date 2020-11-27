# mask_rcnn.res50.fpn.coco.1x  

seed: 40639951

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.390
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.586
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.424
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.227
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.418
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.518
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.321
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.504
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.528
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.334
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.562
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.679
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 39.021 | 58.557 | 42.383 | 22.730 | 41.768 | 51.807 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 53.999 | bicycle      | 30.900 | car            | 43.617 |  
| motorcycle    | 41.528 | airplane     | 63.603 | bus            | 61.997 |  
| train         | 58.452 | truck        | 31.556 | boat           | 26.908 |  
| traffic light | 27.303 | fire hydrant | 66.317 | stop sign      | 65.754 |  
| parking meter | 44.875 | bench        | 22.433 | bird           | 34.645 |  
| cat           | 63.288 | dog          | 57.451 | horse          | 55.339 |  
| sheep         | 47.922 | cow          | 52.589 | elephant       | 59.495 |  
| bear          | 64.997 | zebra        | 65.325 | giraffe        | 65.449 |  
| backpack      | 14.231 | umbrella     | 35.136 | handbag        | 12.100 |  
| tie           | 33.548 | suitcase     | 32.984 | frisbee        | 59.569 |  
| skis          | 22.068 | snowboard    | 31.275 | sports ball    | 44.827 |  
| kite          | 40.238 | baseball bat | 24.287 | baseball glove | 34.566 |  
| skateboard    | 49.629 | surfboard    | 34.610 | tennis racket  | 44.362 |  
| bottle        | 37.733 | wine glass   | 33.998 | cup            | 39.094 |  
| fork          | 31.018 | knife        | 14.323 | spoon          | 12.380 |  
| bowl          | 40.018 | banana       | 23.482 | apple          | 19.229 |  
| sandwich      | 30.732 | orange       | 29.753 | broccoli       | 19.982 |  
| carrot        | 22.038 | hot dog      | 32.653 | pizza          | 49.546 |  
| donut         | 44.382 | cake         | 32.261 | chair          | 24.559 |  
| couch         | 39.026 | potted plant | 24.698 | bed            | 37.645 |  
| dining table  | 25.841 | toilet       | 55.776 | tv             | 52.252 |  
| laptop        | 57.074 | mouse        | 60.105 | remote         | 28.533 |  
| keyboard      | 49.795 | cell phone   | 32.905 | microwave      | 52.627 |  
| oven          | 29.797 | toaster      | 42.594 | sink           | 36.100 |  
| refrigerator  | 52.179 | book         | 14.696 | clock          | 50.380 |  
| vase          | 37.663 | scissors     | 25.027 | teddy bear     | 44.238 |  
| hair drier    | 0.990  | toothbrush   | 15.404 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.352
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.558
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.375
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.169
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.372
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.514
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.299
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.457
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.478
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.285
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.509
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.630
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 35.178 | 55.783 | 37.536 | 16.916 | 37.191 | 51.357 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.193 | bicycle      | 16.402 | car            | 39.858 |  
| motorcycle    | 31.246 | airplane     | 48.925 | bus            | 60.393 |  
| train         | 58.520 | truck        | 32.210 | boat           | 21.753 |  
| traffic light | 26.256 | fire hydrant | 61.565 | stop sign      | 64.528 |  
| parking meter | 45.266 | bench        | 16.228 | bird           | 28.634 |  
| cat           | 64.866 | dog          | 56.102 | horse          | 38.885 |  
| sheep         | 41.193 | cow          | 44.901 | elephant       | 54.718 |  
| bear          | 63.600 | zebra        | 55.473 | giraffe        | 49.737 |  
| backpack      | 13.487 | umbrella     | 42.367 | handbag        | 11.797 |  
| tie           | 31.283 | suitcase     | 34.538 | frisbee        | 59.106 |  
| skis          | 3.179  | snowboard    | 18.815 | sports ball    | 44.685 |  
| kite          | 28.727 | baseball bat | 22.807 | baseball glove | 36.663 |  
| skateboard    | 28.563 | surfboard    | 28.619 | tennis racket  | 51.689 |  
| bottle        | 36.232 | wine glass   | 29.636 | cup            | 39.615 |  
| fork          | 13.937 | knife        | 8.715  | spoon          | 8.603  |  
| bowl          | 37.752 | banana       | 18.534 | apple          | 17.991 |  
| sandwich      | 32.929 | orange       | 29.225 | broccoli       | 19.116 |  
| carrot        | 17.851 | hot dog      | 24.407 | pizza          | 47.841 |  
| donut         | 44.118 | cake         | 31.864 | chair          | 16.074 |  
| couch         | 32.497 | potted plant | 20.350 | bed            | 31.067 |  
| dining table  | 14.424 | toilet       | 57.132 | tv             | 54.669 |  
| laptop        | 57.520 | mouse        | 60.695 | remote         | 26.011 |  
| keyboard      | 48.499 | cell phone   | 32.324 | microwave      | 53.796 |  
| oven          | 27.438 | toaster      | 43.149 | sink           | 33.593 |  
| refrigerator  | 54.699 | book         | 9.151  | clock          | 51.108 |  
| vase          | 35.164 | scissors     | 18.391 | teddy bear     | 41.234 |  
| hair drier    | 1.188  | toothbrush   | 11.938 |                |        |
