# mask_rcnn.res50.fpn.coco.1x.tf-v2  

seed: 23487086

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.411
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.620
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.447
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.253
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.440
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.548
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.328
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.520
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.546
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.362
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.578
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.691
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 41.149 | 62.011 | 44.709 | 25.288 | 44.021 | 54.771 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 54.302 | bicycle      | 31.281 | car            | 43.276 |  
| motorcycle    | 42.778 | airplane     | 63.489 | bus            | 64.080 |  
| train         | 64.529 | truck        | 34.028 | boat           | 27.844 |  
| traffic light | 28.538 | fire hydrant | 66.207 | stop sign      | 60.104 |  
| parking meter | 45.080 | bench        | 23.893 | bird           | 36.209 |  
| cat           | 67.238 | dog          | 63.386 | horse          | 57.419 |  
| sheep         | 51.637 | cow          | 55.050 | elephant       | 64.424 |  
| bear          | 71.404 | zebra        | 65.027 | giraffe        | 63.975 |  
| backpack      | 13.865 | umbrella     | 39.612 | handbag        | 14.152 |  
| tie           | 32.570 | suitcase     | 40.312 | frisbee        | 65.219 |  
| skis          | 21.830 | snowboard    | 34.230 | sports ball    | 47.881 |  
| kite          | 43.271 | baseball bat | 28.229 | baseball glove | 36.939 |  
| skateboard    | 51.052 | surfboard    | 38.586 | tennis racket  | 46.877 |  
| bottle        | 38.215 | wine glass   | 34.513 | cup            | 40.763 |  
| fork          | 32.414 | knife        | 19.045 | spoon          | 16.005 |  
| bowl          | 40.761 | banana       | 23.630 | apple          | 20.932 |  
| sandwich      | 33.603 | orange       | 31.706 | broccoli       | 22.937 |  
| carrot        | 23.962 | hot dog      | 32.855 | pizza          | 51.554 |  
| donut         | 48.960 | cake         | 38.364 | chair          | 27.652 |  
| couch         | 40.810 | potted plant | 25.893 | bed            | 42.440 |  
| dining table  | 27.897 | toilet       | 57.808 | tv             | 55.416 |  
| laptop        | 59.234 | mouse        | 61.024 | remote         | 33.139 |  
| keyboard      | 51.175 | cell phone   | 33.654 | microwave      | 55.708 |  
| oven          | 30.366 | toaster      | 44.249 | sink           | 35.463 |  
| refrigerator  | 57.604 | book         | 16.126 | clock          | 50.778 |  
| vase          | 37.513 | scissors     | 25.914 | teddy bear     | 46.640 |  
| hair drier    | 1.413  | toothbrush   | 23.964 |                |        |


## Evaluation results for segm:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.371
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.589
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.396
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.192
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.392
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.544
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.305
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.473
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.495
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.313
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.523
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.648
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 37.087 | 58.887 | 39.586 | 19.181 | 39.210 | 54.375 |

### Per-category segm AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 46.582 | bicycle      | 17.506 | car            | 39.519 |  
| motorcycle    | 34.158 | airplane     | 50.448 | bus            | 63.379 |  
| train         | 62.786 | truck        | 33.406 | boat           | 22.157 |  
| traffic light | 27.312 | fire hydrant | 62.192 | stop sign      | 62.885 |  
| parking meter | 44.413 | bench        | 17.308 | bird           | 30.155 |  
| cat           | 67.568 | dog          | 59.537 | horse          | 42.384 |  
| sheep         | 45.221 | cow          | 46.488 | elephant       | 58.105 |  
| bear          | 71.099 | zebra        | 54.528 | giraffe        | 48.906 |  
| backpack      | 13.737 | umbrella     | 45.815 | handbag        | 13.487 |  
| tie           | 30.651 | suitcase     | 42.609 | frisbee        | 64.257 |  
| skis          | 1.975  | snowboard    | 21.949 | sports ball    | 47.554 |  
| kite          | 31.826 | baseball bat | 24.101 | baseball glove | 39.122 |  
| skateboard    | 30.776 | surfboard    | 30.749 | tennis racket  | 53.056 |  
| bottle        | 36.894 | wine glass   | 30.190 | cup            | 41.332 |  
| fork          | 15.332 | knife        | 11.870 | spoon          | 10.718 |  
| bowl          | 38.402 | banana       | 19.333 | apple          | 19.897 |  
| sandwich      | 35.427 | orange       | 31.597 | broccoli       | 21.302 |  
| carrot        | 20.187 | hot dog      | 24.054 | pizza          | 50.310 |  
| donut         | 49.468 | cake         | 38.789 | chair          | 18.946 |  
| couch         | 33.734 | potted plant | 21.359 | bed            | 33.530 |  
| dining table  | 15.783 | toilet       | 56.540 | tv             | 57.630 |  
| laptop        | 59.280 | mouse        | 61.718 | remote         | 29.598 |  
| keyboard      | 47.958 | cell phone   | 33.772 | microwave      | 56.136 |  
| oven          | 29.274 | toaster      | 45.060 | sink           | 32.988 |  
| refrigerator  | 58.374 | book         | 10.567 | clock          | 51.082 |  
| vase          | 36.274 | scissors     | 20.565 | teddy bear     | 45.403 |  
| hair drier    | 1.498  | toothbrush   | 15.116 |                |        |
