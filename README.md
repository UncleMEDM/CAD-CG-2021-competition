# single-view RGBD dataset for CAD & CG 2021 competition

### Visualize the data
you can run the draw_bbox.py to visualize the 3d data of the dataset. Open3D is required for the visualization.

### number of class
There are totally 9 class in the dataset.

### How to convert depth image to distance to camera plane
```
distance=(1-depth_value/255.0)*10
```
### How to submit your result
For both 3D object detection and depth estimation, submit your results (zip it if needed), output_report.json generated by the evaluation
script, and your codes and model. Make sure we can run your code from the instruction that you provide. Send all above
files to our email: cad_cg_3dscene_2021@aliyun.com. Maxmimum submission is once per day. <br>
For the result on the test dataset. Please use only the rgb image as inputs to generate results. Please also submit the raw result on test dataset to our email, which should be able to pass the evaluation script.

### Ranking list
#### Depth estimation
Team | CIE | friend | 以此为归 | Inceptio | 万里蹀躞 | 天气太热了 | 全都 | NH106A |
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
rmse | 0.283844 | 0.305452 | 0.314974 | 0.326780 | 0.349783 | 0.434401 | 3.134789 | 69.331764 |
