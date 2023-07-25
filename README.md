# Portfolio_DL_3
DeepLearning Project Porfolio

***
<h2>#2. Project - Chest X-ray Images Pneumonia Classification</h2> 

- Summary
	
	1. Data Source
		- https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
	
	2. Data Preprocessing
		- ImageDataGenerator
      		- rescale: 1./255
      		- image size: (244, 244)
      		- color mode: rgb
			- class mode: sparse<br>
		![Chest_X-ray_Images_with_Label_Names](https://github.com/kkyukkyu99/Portfolio_DL_3/blob/main/Chest_X-ray_Images_with_Label_Names.png)
	
	3. Model & Algorithms
	  	- Transfer Learning(TL)
			- MobileNet(CNN)
	  	- Fine Tunning
  			- Activate function: softmax
			- optimizer: Adam
            - learning_rate: 1e-5
	
	4. Report
    	- loss: 0.0029, accuracy: 0.9992 
        - val_loss: 0.1468, val_accuracy: 0.9375
		![Training_Result](https://github.com/kkyukkyu99/Portfolio_DL_3/blob/main/Training_Result.png)
	
    5. Model
        - loss: 0.0072, accuracy: 0.9973
        - val_loss: 0.0818, val_accuracy: 0.9375
        - (https://github.com/kkyukkyu99/Portfolio_DL_3/blob/main/Chest_X-Ray_Images_Pneumonia_h5_model.h5)