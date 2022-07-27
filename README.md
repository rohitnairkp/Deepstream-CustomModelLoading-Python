# Deepstream-CustomModelLoading-Python
This repo consits of python code which will enable us to load the deepstream trt engine files of the models and run detections over images and draw bounding boxes. The model used here is https://catalog.ngc.nvidia.com/orgs/nvidia/teams/tao/models/peoplenet

We can also run inferences on other pretrained models available in NGC using this code.

## Usage:
Change the "trt_engine_path" to the path of the trt engine file of the deepstream model to be loaded for processing.
Add the input image to "image = cv2.imread"
Add output directory in "cv2.imwrite"

## Run
```
python3 ds_engineload.py
```

## Input 
![Image](/images/people.jpg)

## Output
![Image](/images/people_processed.jpg)
