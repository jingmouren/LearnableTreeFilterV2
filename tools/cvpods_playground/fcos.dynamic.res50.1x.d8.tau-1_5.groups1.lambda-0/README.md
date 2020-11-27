# fcos.dynamic.res50.1x.d8.tau-1_5.groups1.lambda-0  

seed: 4078983

## Evaluation results for bbox:  

```  
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.420
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.600
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.456
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.257
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.460
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.544
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.342
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.565
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.607
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.415
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.654
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.757
```  
|   AP   |  AP50  |  AP75  |  APs   |  APm   |  APl   |  
|:------:|:------:|:------:|:------:|:------:|:------:|  
| 42.041 | 60.049 | 45.597 | 25.749 | 45.979 | 54.386 |

### Per-category bbox AP:  

| category      | AP     | category     | AP     | category       | AP     |  
|:--------------|:-------|:-------------|:-------|:---------------|:-------|  
| person        | 55.874 | bicycle      | 32.225 | car            | 45.024 |  
| motorcycle    | 43.536 | airplane     | 68.588 | bus            | 67.474 |  
| train         | 63.087 | truck        | 36.562 | boat           | 26.610 |  
| traffic light | 28.048 | fire hydrant | 67.603 | stop sign      | 62.582 |  
| parking meter | 43.899 | bench        | 22.540 | bird           | 36.339 |  
| cat           | 68.961 | dog          | 64.107 | horse          | 58.733 |  
| sheep         | 55.502 | cow          | 57.963 | elephant       | 66.042 |  
| bear          | 73.976 | zebra        | 70.158 | giraffe        | 67.060 |  
| backpack      | 15.416 | umbrella     | 40.544 | handbag        | 16.740 |  
| tie           | 32.458 | suitcase     | 39.903 | frisbee        | 66.444 |  
| skis          | 21.830 | snowboard    | 33.399 | sports ball    | 47.454 |  
| kite          | 43.498 | baseball bat | 30.600 | baseball glove | 35.770 |  
| skateboard    | 53.306 | surfboard    | 33.551 | tennis racket  | 49.320 |  
| bottle        | 38.606 | wine glass   | 37.416 | cup            | 43.229 |  
| fork          | 31.735 | knife        | 16.680 | spoon          | 15.910 |  
| bowl          | 41.947 | banana       | 25.041 | apple          | 21.127 |  
| sandwich      | 36.080 | orange       | 32.557 | broccoli       | 24.496 |  
| carrot        | 21.234 | hot dog      | 34.775 | pizza          | 51.763 |  
| donut         | 49.036 | cake         | 36.460 | chair          | 28.882 |  
| couch         | 45.030 | potted plant | 27.844 | bed            | 44.005 |  
| dining table  | 28.212 | toilet       | 61.740 | tv             | 58.081 |  
| laptop        | 58.369 | mouse        | 61.388 | remote         | 32.162 |  
| keyboard      | 49.421 | cell phone   | 35.690 | microwave      | 60.512 |  
| oven          | 35.345 | toaster      | 26.426 | sink           | 36.553 |  
| refrigerator  | 56.909 | book         | 13.543 | clock          | 51.306 |  
| vase          | 37.884 | scissors     | 29.054 | teddy bear     | 48.791 |  
| hair drier    | 10.756 | toothbrush   | 24.577 |                |        |
