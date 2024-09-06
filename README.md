
# Wafer Fault Detection Using Machine Learning

The Wafer Fault Detection project is focused on identifying faults in semiconductor wafers used in manufacturing. Utilizing machine learning, the project aims to classify wafers as either faulty or non-faulty based on sensor data collected during the manufacturing process. The project involves several key steps, including data preprocessing to clean and normalize the data, feature engineering to extract significant features, and the development and evaluation of various machine learning models such as Logistic Regression, SVM, Random Forest, and XGBoost. The best-performing model is deployed in a production environment to provide real-time fault detection, significantly improving quality control in the wafer manufacturing process.
## Author

- [@vishalrajput](https://github.com/vishalrajput29/thyroiddisease)


## Project Lifecycle

![lifecycle](https://github.com/user-attachments/assets/49011b25-3eb6-4353-8f40-5d28c53eb34f)
## Run


To Create an Environment

```cmd
  conda create -p venv python==3.9 -y
```

To Run the Project

```cmd
  python app.py
```

To Run the reqiurement.txt file

```cmd
  pip install -r reqiurement.txt
```


## Data 

Dataset Link : https://drive.google.com/file/d/19WP1Z0vazKLlHt5fp01wsnMHztLkMxx6/view?usp=sharing
## Technologies Used

Here’s a list of technologies you can include in your README file for the phishing classification machine learning project:

---

### Technologies Used

- **Python**: Core programming language for building and deploying the model.
- **Scikit-learn**: For machine learning model development and evaluation.
- **Pandas**: Data manipulation and preprocessing.
- **NumPy**: Numerical computations.
- **Flask**: For creating a lightweight web API to serve the model.
- **GitHub Actions**: CI/CD tools for automating the pipeline, including testing and deployment.
- **Git**: Version control for tracking changes and collaboration.



---

![OIP (1)](https://github.com/user-attachments/assets/c9eea634-f643-4d09-a4f6-596645f8d5f0)
## Data Description


1. **Unnamed: 0**: This likely represents a unique identifier for each wafer, such as the wafer ID.
2. **Sensor-1 to Sensor-590**: These are the features representing sensor readings collected during the wafer manufacturing process. Each sensor captures a specific aspect of the process, such as temperature, pressure, or other physical properties.
3. **Good/Bad**: The target variable, where `1` indicates a good (non-faulty) wafer, and `-1` indicates a bad (faulty) wafer.


## Screenshots

![wafer_page](https://github.com/user-attachments/assets/c7e60c05-72d1-436a-a44b-14b371b6348c)


## Demo

Demo Link :-

https://drive.google.com/file/d/1fBEhVoTF-Y0j8GvSDEHdcQ5QPTn95UmD/view?usp=sharing