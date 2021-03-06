# ML-web-app-with-streamlit (deployed on GCP)

## What is streamlit?
streamlit is a one of the greatest web development libraries avaibale in python. If you do not know HTML, CSS and other web frameworks, streamlit library is a great option to make ML based websites using simple python code.  

## Work flow:
In this project, I have used 3 datasets: 'Iris', 'Breast Cancer' and 'Wine', and 3 machine learning models: 'KNN', 'SVM' and 'Random Forest'. Initially, I made functions to make an interactive UI (added buttons, slider and selectbox). Subsequently, the data was splitted between training and testing. Here, I have used various options, like user can use one of the 3 algorithms on one of the datasets, the screen will give the accuracy and other details of that algorithm on selected dataset.      

![Screenshot 2020-11-30 at 2 40 41 PM](https://user-images.githubusercontent.com/40913151/100572682-3a9ddf80-332a-11eb-92c5-9891d0bc7fbb.png)


## What is new?
I have added a sidebar in UI where user can select the hyperparameters of selected algorithm. For instance, for KNN user can select the K value betweeen 1 to 15 and check the accuracy of the algorithm. In case of Random forest, user have to select two parameters: max_depth, n_estimators. By doing this, one can compare the accuracy by changing hyperparameters of various algorithms on given dataset.


<img src="https://user-images.githubusercontent.com/40913151/100572651-1e9a3e00-332a-11eb-8965-cb0255cc02e7.png" width="400"/> <img src="https://user-images.githubusercontent.com/40913151/100572869-a718de80-332a-11eb-8e89-1db06f37b940.png" width="400"/> 

## How to deploy it on GCP
If you want to deploy this project on google cloud platform, you will need Dockerfile, requirements.txt and app.yaml files.

![Screenshot 2020-12-02 at 2 25 09 AM](https://user-images.githubusercontent.com/40913151/100761899-82feef80-3447-11eb-917a-caf285d57697.png)
