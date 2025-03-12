# Predictive Analytics for Smart Agriculture

## Project Overview
RainWise is a machine learning model designed to predict the probability of rain based on historical weather data. The model is intended to support smart agricultural practices by providing accurate, hyper-local weather predictions to help farmers optimize irrigation, planting, and harvesting schedules.

### Key Features
- Predicts rain probability for the next 21 days
- Utilizes historical weather data with features including temperature, humidity, and wind speed
- Employs a RandomForestClassifier with hyperparameter tuning to optimize accuracy
- Provides actionable insights for agricultural decision-making

---

## Project Structure
```
📦Data-Driven Insights for Agriculture
 ┣ 📂Intellihack_CyperZ_Task01.ipynb # Jupyter notebook with full analysis and mode
 ┣ 📂 Comprehensive project report
 ┣ 📜README.md                    # Project documentation and setup instructions

```


## Setup and Installation
### Prerequisites
- Python 3.8+
- Git (for cloning the repository)
- Jupyter Notebook (for running the `.ipynb` file)

### Installation
1. *Clone the repository:*
bash
git clone https://github.com/danu2003-cy/Intellihack_CypherZ_Task01.git


2. *Create a virtual environment:*
bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate


3. *Add the dataset:*
Place the dataset (customer_behavior_analytics.csv) in the data directory.

### Running the Project

1. *Run the script:*
bash
python Intellihack_CypherZ_Task01.py


2. *View Results:*
The output file customer_segments_output.csv will be generated in the project directory.

---

## Usage
- The Jupyter Notebook provides a step-by-step analysis, from data preprocessing and EDA to model training and evaluation.
- The model outputs probability predictions for the likelihood of rain over the next 21 days.



## Contributing
Feel free to open issues or submit pull requests if you have suggestions or improvements for the project.

---

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

---

## Acknowledgements
- Thanks to IntelliHack for the challenge and opportunity to develop this predictive model.
- Data source: Provided as part of the IntelliHack - Team CyperZ Task 01.

