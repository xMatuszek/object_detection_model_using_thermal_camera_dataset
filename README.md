# Thermal Object Detection

The objective of this project was to develop a model for object detection in the **thermal spectrum**. We implemented **two models** using the large YOLO model on our custom dataset. Out of 16 object classes, we selected 5 (bus, car, other vehicle, person, sign) for this project.

One model was trained on RGB images, while the other was trained on THERMAL images. Both models were trained with the same configurations, including the number of epochs and other hyperparameters. Finally, we compared the performance of both models on thermal images.


### Dataset
We converted the COCO dataset format to be compatible with YOLO. 

You can find the original COCO dataset [here](https://adas-dataset-v2.flirconservator.com/).

### Files 
The file `object_detection_model_using_thermal_camera_dataset.ipynb` contains information about the dataset, classes, conversion of the COCO format to YOLO, training of the RGB model and the thermal model, displaying metric graphs on the validation and test sets for the respective models.

The file `detect_on_thermal_and_rgb_object_detection_models.ipynb` contains the performance of the RGB model and the THERMAL model on an unlabeled dataset and a comparison of both models for the same images
