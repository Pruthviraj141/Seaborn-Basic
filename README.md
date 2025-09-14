# 🛳️ Titanic Dataset Analysis

## 📄 Project Overview
This project analyzes the **Titanic dataset** from [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data).  
The dataset contains passenger information from the RMS Titanic tragedy and is commonly used to learn data analysis and predictive modeling.

Using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**, we explore how different factors like passenger class, gender, age, and fare are related to survival rates.

---

## 📂 Dataset Description
- **Source**: Kaggle – Titanic: Machine Learning from Disaster  
- **Rows**: 891 passengers (training set)  
- **Key Columns**:  
  - `Survived` — 0 = Did not survive, 1 = Survived  
  - `Pclass` — Ticket class (1st, 2nd, 3rd)  
  - `Sex` — Passenger gender  
  - `Age` — Passenger age  
  - `SibSp` — Number of siblings/spouses aboard  
  - `Parch` — Number of parents/children aboard  
  - `Fare` — Ticket price  
  - `Embarked` — Port of embarkation  

The dataset contains a mix of categorical and numerical features, making it ideal for demonstrating various visualization types.

---

## 📊 Visualizations

Below are placeholders for the screenshots of the graphs generated during analysis.  
Replace the image paths (`screenshots/...`) with your actual screenshot file paths after you save them.

1. Survival Count  
### <img width="850" height="547" alt="1" src="https://github.com/user-attachments/assets/9dd515d6-15f4-4c2d-9074-d4624338a2dd" />

### 2. Survival by Gender  
![Survival by Gender](scree<img width="850" height="547" alt="2" src="https://github.com/user-attachments/assets/87d97d76-a334-44d5-ac36-84d6565f180b" />
nshots/survival_by_gender.png)


### 3. Age Distribution of Passengers  
![Age Distribution](screenshots/age<img width="841" height="547" alt="3" src="https://github.com/user-attachments/assets/a8ed709a-a87f-4d98-a543-42ef57e79d61" />
_distribution.png)

### 4. Age Distribution by Passenger Class  
![Age by Class](screenshots/ag<img width="841" height="547" alt="4" src="https://github.com/user-attachments/assets/c97eef11-698a-4576-a2ee-3cb2b2809420" />
e_by_class.png)

### 5. Fare Distribution by Class and Survival  
![Fare by Class and Survival](screenshots/fare_by_class_su<img width="850" height="547" alt="5" src="https://github.com/user-attachments/assets/4c4c33c5-c8b9-4d2c-8ecf-7d2c4a7d25fc" />
rvival.png)

### 6. Correlation Heatmap of Numeric Features  
![Correlation Heatmap](screenshots/correlation_h<img width="768" height="528" alt="6" src="https://github.com/user-attachments/assets/c2fdacdc-0043-4d68-9433-68af61a42c7e" />
eatmap.png)

---

## 💡 Insights from the Visualizations

- **Gender and Survival**  
  A much higher proportion of **female passengers survived** compared to male passengers.

- **Passenger Class**  
  Passengers in **1st class** had the highest survival rates; those in 3rd class had the lowest.

- **Age Distribution**  
  - Most passengers were between **20 and 40 years old**.  
  - Children and very young passengers appear more likely to survive than middle-aged adults.

- **Fare vs. Class**  
  - Higher fares correspond to higher ticket classes.  
  - These passengers also show higher survival rates.

- **Correlation Between Features**  
  `Fare` is negatively correlated with `Pclass` (higher class = higher fare).  
  `Survived` shows moderate correlation with `Sex` and `Pclass`, but weak correlation with family size variables.

---

## 🛠️ Tools Used
- Python 3.x  
- Jupyter Notebook  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📑 How to Reproduce
1. Download the dataset from [Kaggle](https://www.kaggle.com/c/titanic/data).  
2. Run `titanic_analysis.ipynb` or `titanic_analysis.py` to generate plots.  
3. Save the generated graphs into a folder called `screenshots/`.  
4. Replace the image placeholders above with the paths to your actual screenshots.

---

