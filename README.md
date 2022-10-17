## Heart-Disease-Prediction 

### Overview

A simple web application which uses Machine Learning algorithm to predict the heart condition of a person by providing some inputs about the person health like age, gender, blood pressure, cholesterol level etc built using `Flask`.
 


 
## Tech Stack Used
1. Python  
2. Machine Learning algorithms
3. Flask


**About the repository Structure :**

- Project consist `app.py` script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
- `prediction.py` contains code to build and train a Machine learning model.
- *templates* folder contains two files `main.html` and `result.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.  
- *static* folder contains file `style.css` which adds some styling and enhance the look of the application. 

### Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

### Step 1: Clone the repository
```bash
git clone https://github.com/sethusaim/Sensor-Fault-Detection.git
```

### Step 2- Create a conda environment after opening the repository

```bash
conda create -n sensor python=3.8.0 -y
```

```bash
conda activate sensor
```

### Step 3 - Install the requirements
```bash
pip install -r requirements.txt
```


### Step 4 - Run the application server
```bash
python app.py
```


### Technologies used 

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  


[![Flask](https://github.com/jalbertsr/logo-badge-images/blob/master/img/rsz_flask.png?raw=true)](http://flask.pocoo.org/)  


### Future work 

- Improve model performance.
- Add more better styling to the user interface.



**Some Useful Resources**

- **Flask Quickstart Documentation** : [https://flask.palletsprojects.com/en/1.1.x/quickstart/](https://flask.palletsprojects.com/en/1.1.x/quickstart/)


### Output
![Screenshot (52)](https://user-images.githubusercontent.com/54884765/196180844-f85dc94e-542a-404f-aaea-5434201dc599.png)
