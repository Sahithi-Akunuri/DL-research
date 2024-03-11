# DL-research

Saliency detection identifies the visually prominent and attention-grabbing items in a picture. The current study focuses on identifying saliency detection methods utilizing a Multi-Stream Convolution Neural Network. The basic goal is to train a CNN model that collects contextual information and multiscale characteristics. Different measures like as f-measure, recall, accuracy, and MAE are utilized to determine how well our model performs in comparison to other models. We also utilized cross-dataset assessment to determine how well our model performs with unknown data and its generalization capabilities. 

Saliency detection is a computer vision algorithm that identifies attention-grabbing items inside an image. It should not be confused with image or object segmentation, which is application dependent. Saliency detection is the process of identifying a salient item from the perspective of the human visual system. Saliency detection is often connected with two tasks: first, identifying the salient item and then segmenting such things. It has recently been used to object detection, image retrieval, picture and video compression, video summarization, image quality evaluation, visual tracking, human-robot interaction, and non-photorealistic rendering. 

Because saliency detection is not a new field of study, several approaches have been developed to locate saliency. The current study is based on Convolution Neural Network (CNN) training across many datasets. Cross-dataset entails training a model on one dataset and testing it on another. The procedure is used to determine the model's performance on an unknown dataset. The models that perform as predicted over several datasets are said to be more robust. Furthermore, the model employs parallel multi-stream CNN networks. 


These are some of our results:

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/3449feac-6a29-42a4-bd85-70d03b0317c2)

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/c6ab6883-0e4f-4b45-99cf-2af6c66de998)

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/bcc6c336-c5f0-4386-901d-7173efc8eb17)

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/b987b1b1-fc75-478f-bd26-4366a4d33f2a)

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/15bb94c1-5eef-4281-96be-b4fb4baf2c77)

Analysis:

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/5f87d8f4-aeea-409e-a93d-fdf1ca5ad841)
Fig1. Results of saliency detection of various models: a. Original Image b. IT c. MZ d. SR e. OUR

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/ad5f4a26-8805-439b-9709-495cfb3156dd)
Fig2. Comparison of precision, recall and F-measure employed for various methods 

![image](https://github.com/Sahithi-Akunuri/DL-research/assets/111894343/41ecfbf0-b5d9-41c8-be02-4993e4fc61be)
Fig3. Comparison of mean absolute error (MAE) employed for various methods 
