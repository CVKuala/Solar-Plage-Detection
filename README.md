# Solar_Plage_segmentation

A new pipeline to segment the solar plage regions in the Ca II spectroheliogram series. The file "solar_plage_gt.py" once executed will generate segmentation maps of the solar plage regions which are the bright spots present on the solar images. The entire pipeline as illustrated below consists of various steps including blurring, Contrastive limited adaptive histogram equalization (CLAHE) as well as outlier detection to eliminate erroneously segmented regions in the images.

![image](https://user-images.githubusercontent.com/90802245/190999586-33806486-e0bc-42f8-90bf-f0959b88bf83.png)

A visualization of this process is given below,  Do note that step 2 illustrates CLAHE applied to original image -


![image](https://user-images.githubusercontent.com/90802245/191000190-fd551cb5-c3ef-4b12-9f2b-3f4244a348a8.png)


Further, we have introduced a deep learning component by experimenting with segmentation models to improve generalizations in the detection of solar plages. These models are less likely to segment the large erroneous bright regions, thus improving the quality of segmentation maps.

![image](https://user-images.githubusercontent.com/90802245/191002396-19baf045-ae0b-4f37-867e-d4e5cf4030e0.png)

![image](https://user-images.githubusercontent.com/90802245/191002943-571438c0-4287-496c-a0f7-b1e0d3281be1.png)


