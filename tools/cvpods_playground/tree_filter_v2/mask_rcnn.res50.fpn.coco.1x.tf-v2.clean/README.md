# mask_rcnn.res50.fpn.coco.1x.tf-v2.clean  

seed: 40017284

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.411
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.618
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.449
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.238
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.441
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.547
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.327
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.519
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.546
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.349
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.580
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.692
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 41.093 | 61.758 | 44.900 | 23.833 | 44.052 | 54.664 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 54.315 | bicycle      | 30.124 | car            | 43.941 |  
| motorcycle    | 42.800 | airplane     | 65.107 | bus            | 63.899 |  
| train         | 64.293 | truck        | 33.177 | boat           | 27.331 |  
| traffic light | 27.936 | fire hydrant | 67.133 | stop sign      | 62.540 |  
| parking meter | 41.812 | bench        | 23.506 | bird           | 36.426 |  
| cat           | 66.494 | dog          | 61.144 | horse          | 56.330 |  
| sheep         | 52.644 | cow          | 55.483 | elephant       | 63.752 |  
| bear          | 73.185 | zebra        | 64.253 | giraffe        | 62.470 |  
| backpack      | 13.867 | umbrella     | 39.095 | handbag        | 14.306 |  
| tie           | 31.341 | suitcase     | 39.115 | frisbee        | 67.028 |  
| skis          | 22.204 | snowboard    | 33.872 | sports ball    | 48.248 |  
| kite          | 42.870 | baseball bat | 29.645 | baseball glove | 37.426 |  
| skateboard    | 51.958 | surfboard    | 37.757 | tennis racket  | 47.734 |  
| bottle        | 38.792 | wine glass   | 34.904 | cup            | 40.987 |  
| fork          | 32.797 | knife        | 18.305 | spoon          | 15.808 |  
| bowl          | 40.495 | banana       | 24.872 | apple          | 20.665 |  
| sandwich      | 33.492 | orange       | 31.135 | broccoli       | 23.767 |  
| carrot        | 24.508 | hot dog      | 33.495 | pizza          | 52.133 |  
| donut         | 49.364 | cake         | 37.539 | chair          | 27.356 |  
| couch         | 42.114 | potted plant | 26.790 | bed            | 43.559 |  
| dining table  | 27.904 | toilet       | 58.632 | tv             | 55.417 |  
| laptop        | 59.313 | mouse        | 62.426 | remote         | 32.439 |  
| keyboard      | 51.194 | cell phone   | 35.173 | microwave      | 48.737 |  
| oven          | 32.639 | toaster      | 38.054 | sink           | 38.251 |  
| refrigerator  | 56.563 | book         | 16.286 | clock          | 49.020 |  
| vase          | 37.472 | scissors     | 29.345 | teddy bear     | 45.777 |  
| hair drier    | 0.825  | toothbrush   | 22.506 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.371
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.587
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.395
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.180
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.394
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.544
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.305
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.472
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.495
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.301
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.527
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.648
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 37.089 | 58.682 | 39.509 | 17.993 | 39.417 | 54.394 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.722 | bicycle      | 17.085 | car            | 40.166 |  
| motorcycle    | 33.602 | airplane     | 50.554 | bus            | 63.359 |  
| train         | 62.407 | truck        | 32.675 | boat           | 22.785 |  
| traffic light | 26.901 | fire hydrant | 62.443 | stop sign      | 63.928 |  
| parking meter | 42.508 | bench        | 16.475 | bird           | 29.951 |  
| cat           | 66.531 | dog          | 58.844 | horse          | 39.986 |  
| sheep         | 46.142 | cow          | 47.284 | elephant       | 57.721 |  
| bear          | 70.930 | zebra        | 55.422 | giraffe        | 47.738 |  
| backpack      | 14.459 | umbrella     | 46.868 | handbag        | 13.474 |  
| tie           | 29.577 | suitcase     | 41.658 | frisbee        | 65.509 |  
| skis          | 3.116  | snowboard    | 21.395 | sports ball    | 47.078 |  
| kite          | 31.230 | baseball bat | 25.273 | baseball glove | 39.359 |  
| skateboard    | 29.587 | surfboard    | 31.002 | tennis racket  | 54.559 |  
| bottle        | 37.503 | wine glass   | 31.468 | cup            | 41.378 |  
| fork          | 14.878 | knife        | 11.515 | spoon          | 12.287 |  
| bowl          | 38.114 | banana       | 19.237 | apple          | 20.288 |  
| sandwich      | 34.501 | orange       | 30.868 | broccoli       | 21.846 |  
| carrot        | 21.007 | hot dog      | 25.996 | pizza          | 49.922 |  
| donut         | 48.891 | cake         | 37.151 | chair          | 18.383 |  
| couch         | 36.113 | potted plant | 22.123 | bed            | 34.037 |  
| dining table  | 16.001 | toilet       | 58.570 | tv             | 57.354 |  
| laptop        | 58.905 | mouse        | 62.325 | remote         | 28.720 |  
| keyboard      | 49.512 | cell phone   | 33.769 | microwave      | 51.285 |  
| oven          | 30.071 | toaster      | 43.430 | sink           | 34.342 |  
| refrigerator  | 58.448 | book         | 10.608 | clock          | 50.235 |  
| vase          | 36.270 | scissors     | 23.703 | teddy bear     | 43.210 |  
| hair drier    | 0.957  | toothbrush   | 15.593 |                |        |
