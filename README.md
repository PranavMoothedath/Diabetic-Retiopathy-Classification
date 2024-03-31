# Diabetic-Retiopathy-Classification
This was part of our college courses' data science project.
Diabetic retinopathy, a complication of diabetes mellitus that affects the retina, is the leading cause of preventable blindness. Early detection and timely treatment are crucial for preventing vision loss.
![actual_features](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/9575c292-ebed-4d99-ac80-2379ed841259)

In total, the dataset wehave chosen, https://www.kaggle.com/datasets/tanlikesmath/diabetic-retinopathy-resized, comprises of 35216 images. This dataset includes pictures of both the left and right eye retinas of the subjects under consideration.
![oghist](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/79517338-bba9-4965-8d47-9d1fbea69f08)

Distribution of images is as follows:
No diabetic retinopathy: 25810 images
Mild diabetic retinopathy: 5292 images
Moderate diabetic retinopathy: 2443 images
Severe diabetic retinopathy: 873 images
Proliferative diabetic retinopathy: 708 images
Our project was divided into 3 phases:
1) Visualization
2) Preprocessing
3) Model Making

Visualization:
Statistics:
![stats](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/ca424eb9-de00-46b6-9fca-dee0b0f76949)

PCA Visualization:
![pca_vis](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/dd2d3364-0daf-4725-a61d-f7ba55159d88)

Scatter Plot of Image Pixel Values:
![scatter_plot](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/b1311993-c816-426a-822f-6e4f8b7c7b16)

Pixel Intensity Plots:
![pixel_plot](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/e58588bf-50a6-483c-a695-78507394df58)

3D Pixel intensity plots:
![3d_pixel](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/d3519ff3-f861-4195-af51-dbe98b25d4be)

Preprocessing:
CLAHE ( CONTRAST LIMITED ADAPTIVE HISTOGRAM EQUIVALENCE ):
![clahe+he](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/9ee1894c-48d4-4c13-9936-e5e438ec365c)

KRISH CROPPING ( OWN DISCOVERY, WE PERFORMED 8 DIFFERENT KERNEL'S CONVOLUTIONAL OPERATIONS ON IMAGES ):
CANNY EDGE DETECTION:
![canny_edge_detect](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/094886bc-874d-41bd-92cd-85edec42d8eb)

GAUSSIAN CIRCLE CROP ( OWN DISCOVERY, KEPT CIRCLE AS SAME SIZE FOR ALL IMAGES FOR CONSTANCY ):
![gauss_circle](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/648836c8-100a-4eb4-bd79-685021208c71)

Modelling:
Checked Multiple models including
DENSENET121:
![densenet121](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/24bb07ce-1ebb-4dad-a03a-cb5346974882)

INCEPTIONV3:
![incv3](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/eda77a95-9fbc-48c0-bf38-704e8b51c25e)

MOBILENET:
![mobilenet](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/d4e3058c-c428-466e-883b-a2c1f5431c5d)

EFFICIENTB3:
![effb3](https://github.com/PranavMoothedath/Diabetic-Retiopathy-Classification/assets/165509773/5703271a-6b10-49b5-9827-2939c22e37e5)

Based on all our approaches, we got high accuracy with MobileNet architecture with (Gaussian Blur and Circle Crop) Preprocessing !
Technique.
