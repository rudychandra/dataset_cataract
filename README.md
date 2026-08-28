Dataset Source Class Used Number of Images
1.	https://www.kaggle.com/datasets/rifdana/katarak 
-	Normal: 24
-	Immature: 12
-	Mature: 16
2.	https://www.kaggle.com/datasets/alexandramohammed/cataract-image 
-	Mature: 23
3.	https://www.kaggle.com/datasets/nandanp6/cataract-image-dataset 
-	Normal: 20
-	Mature: 26
4.	https://universe.roboflow.com/image-katarak/klasifikasi-stadium-katarak-zfeoi 
-	Normal: 47
-	Immature: 104
-	Mature: 44
5.	https://www.kaggle.com/datasets/mohammedgamal37l30/eye-cataractmature-immature-normal 
-	Normal: 7
-	Immature: 9
-	Mature: 16
6.	https://www.kaggle.com/datasets/thiagosantosborges/cataracteyeskaggle 
-	Normal: 21
7.	Independent eye image data
-	Normal: 6

Total:
-	Normal: 125
-	Immature: 125
-	Mature: 125

Resizing process was performed using bilinear interpolation method

Performing preprocessing using five techniques, namely: 
- Flipping
- Random rotation within the range of -15° to +15°
- Shear transformations
- Brightness adjustment
- Random contrast adjustment within the range of -10% to 10%.

The five augmentation methods applied will result in four types of new images. 
The five augmentation techniques applied will result in five types of new images.  
After image processing, the resulting dataset contains 1,675 images, with 625 images per category
