# Airlines EDA

## Installation

#### Clone the repo

```
git clone https://github.com/ayushsubedi/airlines_eda
```

#### CD into the cloned directory and create a virtualenv

```
python -m venv env
```

### Enable virtualenv

```
source env/bin/activate
```

### Install dependency packages from requirements.txt

```
pip install -r requirements.txt
```

### Start notebook

```
jupyter-lab
```


# Proposal

### Proposal requirements
## At least one **large, real dataset**
  - The source of the dataset [databend.rs](https://databend.rs/doc/learn/analyze-ontime-with-databend-on-ec2-and-s3) and it is compiled using data provided by Research and Innovative Technology Administration (RITA), Bureau of Transportation Statistics.
  - There are 202 million rows, and 109 columns
  - The size of the tabular dataset is ~ 65 GB
  - The dataset is up to date. There are in average ~ 6 million data points for each year starting from 1988 all the way to 2021. 
  - [Full list of columns](https://github.com/ayushsubedi/airlines_eda/blob/main/assets/ontime_table.md)

## Some **non-trivial** analysis/computation/algorithms performed on the dataset
- Exploratory Data Analysis and Visualization
- Outlier detection (Covid?)
- PCA 
- Feature Selection
- Supervised Learning (Regression and Classification)

## an **interactive** user interface that interacts with the algorithm
- Web based user interface

## The problem to address
- Airlines delay

## Why you want to do it 
-

## How you will do it (what tools? e.g., SQLite, PostgreSQL, Hadoop, Kinect, iPad, etc.)
- Pyspark, Python data science stack (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn), Plotly 
- SQLite as the db
- Flask/Streamlit for inputs and interactivity with algorithm
- Tableau for EDA reporting (embedded within Flask/Streamlit)
- Heroku for deployment 

## How your approach is better than the state of the art, why it may succeed, and when it does, what differences will it make, how you will measure success, how long it's gonna take, etc.

### 9 Heilmeier questions
- What are you trying to do? Articulate your objectives using absolutely no jargon.
- How is it done today; what are the limits of current practice?
- What's new in your approach? Why will it be successful?
- Who cares?
- If you're successful, what difference and impact will it make, and how do you measure them (e.g., via user studies, experiments, ground truth data, etc.)?
- What are the risks and payoffs?
- How much will it cost?
- How long will it take?
- What are the midterm and final "exams" to check for success? How will progress be measured?

### Innovation (30%)

### Literatures Reveiw (60%)

### Plan of activities (10%)


# Possible Problem Statements

The problem statements are from https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009

- When is the best time of day/day of week/time of year to fly to minimise delays?
- Do older planes suffer more delays?
- How does the number of people flying between different locations change over time?
- How well does weather predict plane delays?
- Can you detect cascading failures as delays in one airport create delays in others? Are there critical links in the system?

