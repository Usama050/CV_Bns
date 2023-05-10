# CV_Bns
In this Assignment we applied segmentaion on our dataset using YOLO and Detectron2 for Custom Instance Segmentation.
We followed the following step to do this task.
1. Took Images of different Object using Mobile camera.
2. Then using roboflow to do the annotate the image.
3. ![image](https://github.com/Usama050/CV_Bns/assets/113973096/0616991e-333a-4513-be7a-01897f38cbf2)
4. Then Generate the dataset using roboflow
5. ![image](https://github.com/Usama050/CV_Bns/assets/113973096/6d2b05e4-76ed-47ba-9d36-bad9e9bbac10)
![image](https://github.com/Usama050/CV_Bns/assets/113973096/11c29da6-8143-4ee6-86bb-e8d0d9124183)
6. After generating the dataset we apply YOLOv8 for segmentation.
7. Result of YOLOv8.![image](https://github.com/Usama050/CV_Bns/assets/113973096/24254c15-1e75-44b2-a405-c03d091f1bdc)
8. You can find all result in Colab file.
9. After that applied Detectron on same data set.
10. Results for Detectrons.![image](https://github.com/Usama050/CV_Bns/assets/113973096/bde48069-b1e0-4a05-a0e1-8877d3b4e2ec)
![image](https://github.com/Usama050/CV_Bns/assets/113973096/23c7d9bd-431a-4424-b176-90b9a7f727d4)
Note:some images are not detected. It is because first I did bondingbox and thne I do segmentation in Roboflow, so that is why these pics are not detectable.


