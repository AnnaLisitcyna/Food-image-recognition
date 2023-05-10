# Food-image-recognition
Determining the calories of dishes by photo

At the moment, calorie counting applications are widespread. However, it takes a lot of time, desire, as well as accurate measurements of the weight of dishes ingredients by eye. The essence of the proposed project is to estimate the number of calories in a dish based on an image. The relevance of this project is dictated by various categories of people who can become potential users. Firstly, these are people who follow diets for health reasons,it can also be those who want to be thin and are on diets or count calories regularly, the next category is athletes who must monitor the number of calories consumed to maintain physical fitness or achieve some fitness goal.
We propose to make an application where the user will upload a photo of his meal, and as a result, receive a calculation of calories and proteins, fats and carbohydrates with an accuracy of 95%. It is assumed that the algorithm will be trained on collections with recipes, where ingredients, grams, calories are described in detail. The algorithm will have to take into account the category of food, cooking method and the volume to calculate the calorie content of the entire dish.

We conducted five experiments with following models MobileNetV2, Efficient Net, InceptionV3, ResNet50V2, VGG16. At the moment, the best performance was shown by the Efficient Net model: loss = 2.1718, AUC =0.9221, overall accuracy = 0.53. Of course, the model should be improved and more experiments carried out in order to achieve target accuracy score, we are already working on it, but so far this is the best result that has been achieved.

To use the provided code - just download the necessary model and run it in Kaggle
