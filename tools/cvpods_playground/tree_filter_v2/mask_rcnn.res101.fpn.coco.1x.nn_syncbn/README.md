# mask_rcnn.res50.fpn.coco.1x.nn_syncbn  

seed: 14644926

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.387
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.584
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.423
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.227
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.413
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.509
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.321
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.503
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.526
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.336
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.556
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.672
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 38.696 | 58.409 | 42.267 | 22.738 | 41.338 | 50.944 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 53.837 | bicycle      | 29.005 | car            | 43.506 |  
| motorcycle    | 42.071 | airplane     | 61.429 | bus            | 62.860 |  
| train         | 56.858 | truck        | 32.452 | boat           | 26.469 |  
| traffic light | 27.452 | fire hydrant | 64.138 | stop sign      | 64.127 |  
| parking meter | 40.685 | bench        | 22.082 | bird           | 35.903 |  
| cat           | 62.237 | dog          | 55.194 | horse          | 55.582 |  
| sheep         | 50.371 | cow          | 50.576 | elephant       | 59.383 |  
| bear          | 62.192 | zebra        | 65.312 | giraffe        | 64.387 |  
| backpack      | 13.482 | umbrella     | 36.510 | handbag        | 12.133 |  
| tie           | 32.906 | suitcase     | 33.104 | frisbee        | 60.864 |  
| skis          | 20.602 | snowboard    | 32.096 | sports ball    | 45.878 |  
| kite          | 40.241 | baseball bat | 24.769 | baseball glove | 32.950 |  
| skateboard    | 48.373 | surfboard    | 35.287 | tennis racket  | 43.830 |  
| bottle        | 37.426 | wine glass   | 34.268 | cup            | 39.936 |  
| fork          | 30.062 | knife        | 15.832 | spoon          | 12.452 |  
| bowl          | 40.845 | banana       | 24.651 | apple          | 19.232 |  
| sandwich      | 29.909 | orange       | 29.628 | broccoli       | 20.221 |  
| carrot        | 20.779 | hot dog      | 31.975 | pizza          | 50.089 |  
| donut         | 41.566 | cake         | 34.116 | chair          | 25.253 |  
| couch         | 39.438 | potted plant | 24.409 | bed            | 38.740 |  
| dining table  | 26.462 | toilet       | 55.751 | tv             | 52.736 |  
| laptop        | 56.444 | mouse        | 59.807 | remote         | 27.788 |  
| keyboard      | 48.672 | cell phone   | 33.439 | microwave      | 50.953 |  
| oven          | 30.984 | toaster      | 35.983 | sink           | 34.728 |  
| refrigerator  | 52.026 | book         | 15.480 | clock          | 48.471 |  
| vase          | 35.695 | scissors     | 25.666 | teddy bear     | 43.893 |  
| hair drier    | 0.000  | toothbrush   | 18.739 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.349
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.556
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.374
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.169
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.369
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.515
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.299
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.457
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.477
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.288
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.505
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.630
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 34.941 | 55.587 | 37.428 | 16.860 | 36.859 | 51.495 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.163 | bicycle      | 16.986 | car            | 39.793 |  
| motorcycle    | 32.031 | airplane     | 48.331 | bus            | 61.569 |  
| train         | 57.774 | truck        | 32.222 | boat           | 21.214 |  
| traffic light | 26.426 | fire hydrant | 60.825 | stop sign      | 62.708 |  
| parking meter | 40.401 | bench        | 15.410 | bird           | 29.191 |  
| cat           | 64.497 | dog          | 54.936 | horse          | 39.925 |  
| sheep         | 43.195 | cow          | 43.856 | elephant       | 55.475 |  
| bear          | 62.553 | zebra        | 56.007 | giraffe        | 47.598 |  
| backpack      | 13.147 | umbrella     | 43.329 | handbag        | 11.873 |  
| tie           | 30.337 | suitcase     | 33.860 | frisbee        | 60.187 |  
| skis          | 2.340  | snowboard    | 20.497 | sports ball    | 45.416 |  
| kite          | 28.502 | baseball bat | 22.819 | baseball glove | 35.265 |  
| skateboard    | 28.530 | surfboard    | 28.470 | tennis racket  | 50.615 |  
| bottle        | 35.973 | wine glass   | 30.848 | cup            | 40.323 |  
| fork          | 15.119 | knife        | 9.305  | spoon          | 8.798  |  
| bowl          | 38.258 | banana       | 19.138 | apple          | 18.231 |  
| sandwich      | 32.426 | orange       | 29.347 | broccoli       | 19.052 |  
| carrot        | 17.742 | hot dog      | 23.275 | pizza          | 48.624 |  
| donut         | 42.517 | cake         | 33.881 | chair          | 16.567 |  
| couch         | 32.966 | potted plant | 20.528 | bed            | 31.049 |  
| dining table  | 14.942 | toilet       | 55.849 | tv             | 54.820 |  
| laptop        | 57.227 | mouse        | 60.667 | remote         | 25.245 |  
| keyboard      | 47.237 | cell phone   | 32.459 | microwave      | 51.662 |  
| oven          | 28.966 | toaster      | 34.847 | sink           | 32.600 |  
| refrigerator  | 54.882 | book         | 9.407  | clock          | 49.170 |  
| vase          | 35.102 | scissors     | 17.840 | teddy bear     | 41.866 |  
| hair drier    | 0.000  | toothbrush   | 12.257 |                |        |
