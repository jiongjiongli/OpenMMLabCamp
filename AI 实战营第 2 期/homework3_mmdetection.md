# MMDetection Train

```
06/10 20:03:05 - mmengine - INFO - Exp name: rtmdet_tiny_1xb12-40e_balloon_20230610_195844
06/10 20:03:08 - mmengine - INFO - Epoch(train) [40][5/6]  lr: 9.4971e-06  eta: 0:00:00  time: 0.8506  data_time: 0.5101  memory: 1623  loss: 0.7006  loss_cls: 0.4912  loss_bbox: 0.2094
06/10 20:03:08 - mmengine - INFO - Exp name: rtmdet_tiny_1xb12-40e_balloon_20230610_195844
06/10 20:03:08 - mmengine - INFO - Saving checkpoint at 40 epochs
06/10 20:03:10 - mmengine - INFO - Epoch(val) [40][ 5/13]    eta: 0:00:00  time: 0.0632  data_time: 0.0231  memory: 307  
06/10 20:03:10 - mmengine - INFO - Epoch(val) [40][10/13]    eta: 0:00:00  time: 0.0595  data_time: 0.0212  memory: 213  
06/10 20:03:10 - mmengine - INFO - Evaluating bbox...
Loading and preparing results...
DONE (t=0.00s)
creating index...
index created!
Running per image evaluation...
Evaluate annotation type *bbox*
DONE (t=0.11s).
Accumulating evaluation results...
DONE (t=0.01s).
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.706
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.820
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.783
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.021
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.535
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.855
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.222
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.754
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.790
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.167
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.706
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.900
06/10 20:03:10 - mmengine - INFO - bbox_mAP_copypaste: 0.706 0.820 0.783 0.021 0.535 0.855
06/10 20:03:10 - mmengine - INFO - Epoch(val) [40][13/13]  coco/bbox_mAP: 0.7060  coco/bbox_mAP_50: 0.8200  coco/bbox_mAP_75: 0.7830  coco/bbox_mAP_s: 0.0210  coco/bbox_mAP_m: 0.5350  coco/bbox_mAP_l: 0.8550  data_time: 0.0177  time: 0.0531
```

# MMDetection Test

```
Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.723
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.830
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.800
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.018
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.574
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.863
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.226
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.756
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.806
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.200
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.724
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.913
06/10 20:07:02 - mmengine - INFO - bbox_mAP_copypaste: 0.723 0.830 0.800 0.018 0.574 0.863
06/10 20:07:02 - mmengine - INFO - Epoch(test) [13/13]  coco/bbox_mAP: 0.7230  coco/bbox_mAP_50: 0.8300  coco/bbox_mAP_75: 0.8000  coco/bbox_mAP_s: 0.0180  coco/bbox_mAP_m: 0.5740  coco/bbox_mAP_l: 0.8630  data_time: 0.0150  time: 0.0741
```





# MMDetection Inference

![Inference](./images/inference_result.png)



# Feature Visualization

![Feature Visualization](./images/featmap_vis_result.png)



# Box AM Visualization

![Box AM Visualization](./images/boxam_vis_result.png)

# Code

[Jupyter Notebook](./notebooks/homework3_mmdetection.ipynb)