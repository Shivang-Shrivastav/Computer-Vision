# Computer-Vision


DOMAIN: Botanical research
• CONTEXT: University X is currently undergoing some research involving understanding the characteristics of
plant and plant seedlings at various stages of growth. They already have have invested on curating sample
images. They require an automation which can create a classifier capable of determining a plant's species from a
photo

• DATA DESCRIPTION: The dataset comprises of images from 12 plant species. Source: https://www.kaggle.com/c/
plant-seedlings-classification/data

• PROJECT OBJECTIVE: University’s management require an automation which can create a classifier capable of
determining a plant's species from a photo

Steps and tasks: [ Total Score: 20 points]
1. Import the data. Analyse the dimensions of the data. Visualise the data.
2. Train tune and test AIML image classifier model using:
• Use supervised learning algorithms for training
• Use neural networks for training
• Use CNN for training
3. Compare the results from the above step along with your detailed observations.
4. Pickle the best performing model.
5. Import the the image in the “ Prediction” folder to predict the class. Display the image. Use the best trained image
classifier model to predict the class

XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

DOMAIN: Entertainment
• CONTEXT: Company X owns a movie application and repository which caters movie streaming to millions of users who on subscription basis.
Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on the
movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer vision
and multimedia experts who need to detect faces from screen shots from the movie scene.

• DATA DESCRIPTION: The dataset comprises of images and its mask where there is a human face.

• PROJECT OBJECTIVE: Face detection from training images.

Steps and tasks: [ Total Score: 20 points]
1. Import the dataset.
2. Create features (images) and labels (mask) using that data.
3. Mask detection model:

● Design a face mask detection model.
Hint: Use U-net along with pre-trained transfer learning models

● Design your own Dice Coefficient and Loss function.
● Train, tune and test the model.

● Evaluate the model using testing data.
4. Use the “Prediction image” as an input to your designed model and display the output of the image.
