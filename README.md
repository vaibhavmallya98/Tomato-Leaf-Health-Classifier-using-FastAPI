# Tomato-Leaf-Health-Classifier-using-FastAPI
This project is a machine learning application designed to classify tomato plant leaf images as healthy or unhealthy. The application is built using FastAPI for the backend and TensorFlow for the machine learning model.

### Features
It classifies images of tomato plant leaves into healthy or unhealthy categories. It utilizes FastAPI to create a RESTful API for serving the model. Convolutional neural network (CNN) with multiple Conv2D and MaxPooling2D layers are used for image processing and classification. 

### Dataset 
Plant Village dataset from Kaggle has been used for training and testing.

### Evaluation 
The model has been evaluated using training accuracy and validation accuracy as metrics. Below are the plots of both metrics against the number of epochs. 

![TomatoClassifierPlot](https://github.com/vaibhavmallya98/Tomato-Leaf-Health-Classifier-using-FastAPI/assets/45683079/7d547e99-6071-4b43-91ee-a8d34d602562)

### Model Output 
Shown below are the outputs predicted by the model vs the actual output. 

![TomatoClassifierOutput](https://github.com/vaibhavmallya98/Tomato-Leaf-Health-Classifier-using-FastAPI/assets/45683079/655678f9-aa30-4f09-9892-de97a2541881)


### Usage
The model's architecture is present in the tomato_disease_classification.ipynb Python Notebook and the saved model has been run as an app using FastAPI framework. The instructions on how to run the FastAPI code have been mentioned in the FastAPI_run.ipynb Python Notebook. Use a tool like Postman to send a POST request to the FastAPI endpoint with an image of a tomato plant leaf. The API will return a classification indicating whether the leaf is healthy or unhealthy.

### FastAPI Output 
Shown below is the classification output of the model after it has been run as an FastAPI application on the Postman app. 
![FastAPI_Postman_Output_Screenshot](https://github.com/vaibhavmallya98/Tomato-Leaf-Health-Classifier-using-FastAPI/assets/45683079/0569d776-f958-4de3-8671-64169e77e96e)

