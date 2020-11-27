# mask_rcnn.res50.fpn.coco.1x.tf-v2.rst  

seed: 56300984

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.410
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.616
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.449
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.244
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.444
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.539
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.330
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.521
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.548
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.357
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.585
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.692
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 41.037 | 61.631 | 44.876 | 24.406 | 44.405 | 53.933 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 54.643 | bicycle      | 30.551 | car            | 43.630 |  
| motorcycle    | 43.309 | airplane     | 63.519 | bus            | 62.612 |  
| train         | 63.841 | truck        | 34.719 | boat           | 27.301 |  
| traffic light | 27.818 | fire hydrant | 66.224 | stop sign      | 62.935 |  
| parking meter | 45.755 | bench        | 24.801 | bird           | 35.845 |  
| cat           | 65.184 | dog          | 60.084 | horse          | 56.903 |  
| sheep         | 52.235 | cow          | 57.896 | elephant       | 62.336 |  
| bear          | 72.208 | zebra        | 65.444 | giraffe        | 64.875 |  
| backpack      | 14.291 | umbrella     | 37.997 | handbag        | 14.693 |  
| tie           | 33.575 | suitcase     | 40.893 | frisbee        | 66.906 |  
| skis          | 21.369 | snowboard    | 37.413 | sports ball    | 47.795 |  
| kite          | 44.764 | baseball bat | 30.101 | baseball glove | 37.434 |  
| skateboard    | 52.306 | surfboard    | 38.909 | tennis racket  | 46.527 |  
| bottle        | 39.709 | wine glass   | 35.979 | cup            | 40.789 |  
| fork          | 31.966 | knife        | 18.628 | spoon          | 15.952 |  
| bowl          | 41.556 | banana       | 24.682 | apple          | 19.834 |  
| sandwich      | 33.873 | orange       | 30.459 | broccoli       | 23.394 |  
| carrot        | 24.577 | hot dog      | 30.018 | pizza          | 53.197 |  
| donut         | 49.907 | cake         | 38.004 | chair          | 27.151 |  
| couch         | 41.573 | potted plant | 27.388 | bed            | 44.137 |  
| dining table  | 27.441 | toilet       | 56.976 | tv             | 53.918 |  
| laptop        | 58.462 | mouse        | 61.089 | remote         | 31.959 |  
| keyboard      | 50.022 | cell phone   | 34.256 | microwave      | 50.031 |  
| oven          | 31.345 | toaster      | 25.127 | sink           | 35.951 |  
| refrigerator  | 58.539 | book         | 15.053 | clock          | 49.347 |  
| vase          | 38.873 | scissors     | 28.271 | teddy bear     | 44.713 |  
| hair drier    | 6.590  | toothbrush   | 22.544 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.368
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.586
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.389
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.183
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.394
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.531
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.307
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.473
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.495
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.309
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.528
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.644
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 36.793 | 58.573 | 38.891 | 18.284 | 39.350 | 53.120 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.874 | bicycle      | 16.982 | car            | 39.789 |  
| motorcycle    | 33.570 | airplane     | 48.821 | bus            | 62.286 |  
| train         | 61.911 | truck        | 33.360 | boat           | 23.022 |  
| traffic light | 26.813 | fire hydrant | 62.182 | stop sign      | 63.232 |  
| parking meter | 45.858 | bench        | 16.923 | bird           | 29.865 |  
| cat           | 65.140 | dog          | 58.205 | horse          | 40.279 |  
| sheep         | 45.382 | cow          | 48.147 | elephant       | 55.313 |  
| bear          | 69.847 | zebra        | 55.935 | giraffe        | 47.619 |  
| backpack      | 13.859 | umbrella     | 45.417 | handbag        | 13.984 |  
| tie           | 31.349 | suitcase     | 41.598 | frisbee        | 64.497 |  
| skis          | 2.609  | snowboard    | 23.811 | sports ball    | 47.453 |  
| kite          | 32.892 | baseball bat | 25.444 | baseball glove | 39.808 |  
| skateboard    | 30.786 | surfboard    | 31.875 | tennis racket  | 53.093 |  
| bottle        | 37.611 | wine glass   | 32.497 | cup            | 41.042 |  
| fork          | 14.197 | knife        | 12.057 | spoon          | 12.030 |  
| bowl          | 38.875 | banana       | 19.407 | apple          | 19.519 |  
| sandwich      | 34.619 | orange       | 30.164 | broccoli       | 21.557 |  
| carrot        | 21.768 | hot dog      | 20.557 | pizza          | 51.650 |  
| donut         | 50.686 | cake         | 38.326 | chair          | 17.893 |  
| couch         | 33.915 | potted plant | 23.305 | bed            | 35.560 |  
| dining table  | 16.391 | toilet       | 56.118 | tv             | 56.536 |  
| laptop        | 57.981 | mouse        | 60.120 | remote         | 28.978 |  
| keyboard      | 48.960 | cell phone   | 33.082 | microwave      | 51.074 |  
| oven          | 29.046 | toaster      | 28.103 | sink           | 33.334 |  
| refrigerator  | 58.084 | book         | 10.580 | clock          | 49.328 |  
| vase          | 37.218 | scissors     | 21.669 | teddy bear     | 42.631 |  
| hair drier    | 5.743  | toothbrush   | 15.402 |                |        |
