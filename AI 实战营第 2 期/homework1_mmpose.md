

# MMDet Evaluation

```
Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.820
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.959
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.959
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.820
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.857
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.857
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.857
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.857
06/07 02:20:33 - mmengine - INFO - bbox_mAP_copypaste: 0.820 0.959 0.959 -1.000 -1.000 0.820
06/07 02:20:33 - mmengine - INFO - Epoch(test) [42/42]    coco/bbox_mAP: 0.8200  coco/bbox_mAP_50: 0.9590  coco/bbox_mAP_75: 0.9590  coco/bbox_mAP_s: -1.0000  coco/bbox_mAP_m: -1.0000  coco/bbox_mAP_l: 0.8200  data_time: 0.1063  time: 0.1421
```





# MMPose Evaluation

```
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets= 20 ] =  0.754
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets= 20 ] =  1.000
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets= 20 ] =  0.970
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets= 20 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets= 20 ] =  0.754
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 20 ] =  0.786
 Average Recall     (AR) @[ IoU=0.50      | area=   all | maxDets= 20 ] =  1.000
 Average Recall     (AR) @[ IoU=0.75      | area=   all | maxDets= 20 ] =  0.976
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets= 20 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets= 20 ] =  0.786
06/07 12:39:37 - mmengine - INFO - Evaluating PCKAccuracy (normalized by ``"bbox_size"``)...
06/07 12:39:37 - mmengine - INFO - Evaluating AUC...
06/07 12:39:37 - mmengine - INFO - Evaluating NME...
06/07 12:39:37 - mmengine - INFO - Epoch(test) [42/42]    coco/AP: 0.753892  coco/AP .5: 1.000000  coco/AP .75: 0.970297  coco/AP (M): -1.000000  coco/AP (L): 0.753892  coco/AR: 0.785714  coco/AR .5: 1.000000  coco/AR .75: 0.976190  coco/AR (M): -1.000000  coco/AR (L): 0.785714  PCK: 0.975057  AUC: 0.137472  NME: 0.039868  data_time: 0.156440  time: 0.205529
```



# MMPose Prediction

## Image

![mmpose_image](./images/mmpose_predict.png)

## Video
<video src="https://github.com/jiongjiongli/OpenMMLabCamp/assets/33146359/ee5a50b4-282c-43bf-8186-1e5f7170e5d4"></video>




# Code

[Jupyter Notebook](./notebooks/homework1_mmpose.ipynb)
