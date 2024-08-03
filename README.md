INTRODUCTION
This research is being carried out using the waterfall model. System analysis is a branch of software engineering that deals with the planning and analysis of a model or software's development before it is designed. Figure 3.1 depicts the first stage of the development of our age prediction software.
LANGUAGE
The python programming language was used for the implementation of this project. The python language is the major language used for data science projects around the world. Quite a number of python libraries used for machine learning and deep learning are used for this project. 
DATASET
We obtained the FFHQ datasets from Kaggle in order to make the predictions. Individuals of various ages are represented in the FFHQ dataset. This dataset contains over 52,000 images and it is also an unlabeled dataset. Due to the grossly limited computational resources to train that much images, 100 images of each age ranges were selected. Age ranges are grouped into 10 classes, these classes include: 0-10, 11-20, 21-30, 31-40, 41-50, 51-60, 61-70, 71-80, 81-90, 91-100.  
DATA PRE-PROCESSING
All the changes made to the raw data prior to feeding it to the machine learning or deep learning algorithm are referred to as preprocessing. For instance, convolutional neural network training on unprocessed images is likely to produce subpar categorization results. Preprocessing is essential for accelerating training.
MODEL
Integrated Development Environment (IDE)
Following the annotations, the images and labels were uploaded to Google Drive. Following that, it was installed on Google Colaboratory. Google Colab is a Google Research product that allows anyone to write and run Python code. It is similar to Jupyter Notebook, but it is hosted on Google Cloud.
Algorithm 
A real-time object detection system called Yolo-v3 can recognize particular items in films, live streams, or still photos. To find an item, the YOLO machine learning system leverages features that a deep convolutional neural network has learned. Because it enables the model to view the entire image during testing, its predictions are influenced by the image's overall context. Convolutional neural network methods like YOLO "rank" regions according to how closely they resemble predetermined classes.
