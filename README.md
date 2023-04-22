# Bank Note Authentication ML App

This is a simple Machine Learning app built with Flask, Flasgger migrated to Streamlit, which aims to authenticate bank notes using the banknote authentication dataset. The model used in this app was trained using a Random Forest Classifier and the dataset source is [Kaggle](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data).
## Installation

To install the required dependencies for this app, run the following command:

```python
pip install -r requirements.txt
```
## Usage
To run the app, execute the following command:
```python
streamlit run app.py
```
Once the app is running, you will see a form with four input fields: variance, skewness, curtosis, and entropy. Enter the values for these fields and click the "Predict" button to see the result.

## Live Demo
[Deployed Demo](https://gauritomar-banknoteauthentication-ml-app-app-x8guho.streamlit.app)

<p align="center">
  <img src="https://user-images.githubusercontent.com/97106972/233763408-69c8c7bd-ca43-4556-8f75-36c07321cd5d.png" width="600" alt="image_description">
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/97106972/233763472-876c30ec-4157-42b9-b5cd-f45ec09f688a.png" width="600" alt="image_description">
</p>



## Credits
This app was created by Krish Naik as part of his online course on Deploy Machine Learning Models using Docker on youtube.



