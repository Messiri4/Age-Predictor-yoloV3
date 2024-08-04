INTRODUCTION:
This research is being carried out using the waterfall model. System analysis is a branch of software engineering that deals with the planning and analysis of a model or software's development before it is designed. Figure 3.1 depicts the first stage of the development of our age prediction software.
<img width="811" alt="Screenshot 2024-08-03 at 21 50 53" src="https://github.com/user-attachments/assets/fe7d74b7-5d0c-4f61-ab74-8990669c6827">

LANGUAGE:
The python programming language was used for the implementation of this project. The python language is the major language used for data science projects around the world. Quite a number of python libraries used for machine learning and deep learning are used for this project. 

DATASET:
We obtained the FFHQ datasets from Kaggle in order to make the predictions. Individuals of various ages are represented in the FFHQ dataset. This dataset contains over 52,000 images and it is also an unlabeled dataset. Due to the grossly limited computational resources to train that much images, 100 images of each age ranges were selected. Age ranges are grouped into 10 classes, these classes include: 0-10, 11-20, 21-30, 31-40, 41-50, 51-60, 61-70, 71-80, 81-90, 91-100. 

DATA PRE-PROCESSING:
All the changes made to the raw data prior to feeding it to the machine learning or deep learning algorithm are referred to as preprocessing. For instance, convolutional neural network training on unprocessed images is likely to produce subpar categorization results. Preprocessing is essential for accelerating training.

MODEL:
Integrated Development Environment (IDE)
Following the annotations, the images and labels were uploaded to Google Drive. Following that, it was installed on Google Colaboratory. Google Colab is a Google Research product that allows anyone to write and run Python code. It is similar to Jupyter Notebook, but it is hosted on Google Cloud.

ALGORITHM: 
A real-time object detection system called Yolo-v3 can recognize particular items in films, live streams, or still photos. To find an item, the YOLO machine learning system leverages features that a deep convolutional neural network has learned. Because it enables the model to view the entire image during testing, its predictions are influenced by the image's overall context. Convolutional neural network methods like YOLO "rank" regions according to how closely they resemble predetermined classes.

DESIGN AND SPECIFICATION
<img width="814" alt="Screenshot 2024-08-03 at 21 52 22" src="https://github.com/user-attachments/assets/c2522c31-d6cb-4ec4-b323-b90546fb18ca">

<img width="814" alt="Screenshot 2024-08-03 at 21 53 01" src="https://github.com/user-attachments/assets/1739c1f1-b7dc-43a1-9546-5c0c6a6c176b">

<img width="812" alt="Screenshot 2024-08-03 at 21 53 44" src="https://github.com/user-attachments/assets/102c2226-8a29-4af9-97e1-fff3cbc6bdfd">

ANNOTATION OF THE IMAGES: 
For the image pre-processing process, images were grouped into 10 classes. Annotation of the images carried out using LabelImg. LabelImg is an opensource tool used for labeling images. It has different features for labeling, but for this research we used the yolo feature. Yolo means You Only Look Once, it is an algorithm for used for object detection. Yolo algorithm was used to detect the malar region in the face. Yolo has different versions, we usedYolo-v3 algorithm for the implementation. 

<img width="1374" alt="Screenshot 2024-08-03 at 21 54 29" src="https://github.com/user-attachments/assets/ec14933f-7068-41dc-a71f-bc93ec2120db">

TRANSFER LEARNING/ FINE TUNING: 
The Yolo algorithm makes use of the darknet framework. Darknet is a fast and accurate neural network framework that also supports CPU and GPU computation. We used transfer learning to fit our image dataset by fine-tuning the darknet neural network.

TRAINING THE MODEL: 
To train our model, we divided the dataset into 70 percent training images and 30 percent testing/validation images. The classification of the images reveals that it is a supervised machine learning problem, with 0-10 representing class (0), 11-20 representing class (1), 21-30 representing class (2), 31-40 representing class (3), 41-50 representing class (4), 51-60 representing class (5), 61-70 representing class (6), 71-80 representing class (7), 81-90 representing class (8), and 91-100 representing class (9) (9).

<img width="819" alt="Screenshot 2024-08-03 at 21 56 26" src="https://github.com/user-attachments/assets/b6b545b2-6270-451d-8f03-0ccbf1828677">

PERFORMANCE EVALUATION:
In this section, the accuracy of the model was tested on three different images from the test set. For the first image, the model detected both malar regions, “person_71_80” for the left malar region, with 94% probability and “person_51_60” for the right malar region, with 89% probability as shown in fig 4.3 and fig 4.4. 
For the second image, the model detected both malar regions, “person_31_40” for the left malar region, with 93% probability and “person_31_40” for the right malar region, with 89% probability as shown in fig 4.5 and fig 4.6.
For the third image, the model detected both malar regions, “person_21_30” and “person_31_40” for the left malar region, with 52% and 42% probability and “person_31_40” for the right malar region, with 90% probability as shown in fig 4.7 and fig 4.8. 

<img width="813" alt="Screenshot 2024-08-03 at 21 58 06" src="https://github.com/user-attachments/assets/34c47180-4aec-4a9e-9dda-6cdcf586565b">

<img width="808" alt="Screenshot 2024-08-03 at 21 59 09" src="https://github.com/user-attachments/assets/23d049bb-70e3-4356-9022-c8007f572ba7">

<img width="767" alt="Screenshot 2024-08-03 at 22 00 37" src="https://github.com/user-attachments/assets/449a6d6f-9979-4e57-9981-04605f783005">

<img width="815" alt="Screenshot 2024-08-03 at 22 01 24" src="https://github.com/user-attachments/assets/900a8102-7749-4eb8-aca6-59ffa43dc6b1">
