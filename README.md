**Dogs vs Cats Image Classifier**

This project is a Flask web application that uses a Convolutional Neural Network (CNN) model trained with Keras to classify images of dogs and cats.
Users can upload an image, and the app will predict whether the image is of a dog or a cat.

Note - 
1. index.html is a template and need to be added in templates folder before you run.
       
2. Tensorflow 2.x version have some methods and functions removed. Check your version before execute

3. And set the runtime to GPU in google collab before running.



Dataset - https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification

#**Step-by-Step Guide**
1. Prerequisites
Ensure you have the following installed on your system:

Python 3.11


2. Clone the Repository
Open a terminal or command prompt.
Clone the repository to your local machine using git clone command.
Navigate into the project directory using the cd command.

3. Set Up a Virtual Environment
Create a virtual environment using the venv module.
Activate the virtual environment:
On Windows, use the activate command from the venv\Scripts directory.
On macOS and Linux, use the source command to activate the virtual environment.

4. Install Required Packages
Install the necessary packages listed in the requirements.txt file using pip install.

5. Download the Trained Model
Download your trained model file (e.g., model.h5).
Save the model file to the project directory.
Open the app.py file and update the MODEL_PATH variable to point to your model file's path.

6. Run the Flask Application
Start the Flask app by running the appropriate command.
Open your web browser and navigate to the local address provided (usually http://127.0.0.1:5000/).

7. Use the Application
On the homepage, use the form to upload an image of a dog or a cat.
Click the "Predict" button.
The app will display the prediction result (whether it's a dog or a cat).
Project Structure
The main application file (app.py) handles routing and prediction.
The templates folder contains HTML templates (index.html and result.html).
The uploads folder stores uploaded images temporarily.
The requirements.txt file lists the Python packages required to run the application.
The Model_Train.ipynb Jupyter notebook is used for training the model (if you need to retrain the model).

Additional Information
Model Training
If you need to train your own model, open the Model_Train.ipynb Jupyter notebook and follow the steps to train and save your model.
License
This project is licensed under the MIT License. Refer to the LICENSE file for details.
Acknowledgments
The model is based on the dataset from the Kaggle competition: Dogs vs. Cats.
Inspiration from various tutorials and articles on image classification with Keras and Flask.


By following these steps, you should be able to set up, run, and use the Dogs vs Cats Image Classifier project on your local machine. If you encounter any issues, please check the configurations and ensure all dependencies are installed correctly.

#Special Thanks for Hunar Intern -internship for this amazing opporunity.
