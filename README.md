# Helmet-Not-Helmet-Object-Detector-using-YOLO
## Dataset Description

The dataset used for this Helmet Detection project was created by combining a publicly available Kaggle helmet detection dataset with a custom dataset developed specifically for this project.

The custom dataset consisted of approximately 123 images collected from publicly available online sources. Among these images, 62 contained individuals wearing helmets, while 61 contained individuals without helmets. All images in the custom dataset were manually annotated using Roboflow, where bounding boxes were created around the target objects.

After annotation, the custom dataset was merged with the Kaggle dataset to increase the diversity and size of the training data. The final merged dataset was then used to train and evaluate a YOLOv8-based object detection model for identifying riders wearing helmets and riders without helmets.

### Tools Used

* Roboflow (Image Annotation and Dataset Management)
* Kaggle Dataset
* YOLOv8 (Object Detection Model)
* Google Colab (Model Training and Evaluation)
