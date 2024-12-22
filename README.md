# Bike-Sharing Dashboard Analysis
As final delivere for certification "Analisis Data Dengan Python"

## Setup Environment - Python

```python
py -m venv .venv
.\.venv\Scripts\activate
pip freeze >  requirements.txt
```

## Path Dataset In Deploy and Local
Path for dataset when deploy in cloud and local
### Local (In directory submission)
```python
day_df = pd.read_csv("dashboard/day_clean_data.csv")
hour_df = pd.read_csv("dashboard/hour_clean_data.csv")
```
### Deploy (root directory "dashboard" in github)
```python
day_df = pd.read_csv("dashboard/day_clean_data.csv")
hour_df = pd.read_csv("dashboard/hour_clean_data.csv")
```
## Run streamlit app
```python
streamlit run dashboard/dashboard.py
```
or 
```python
cd dashboard
streamlit run dashboard.py
```
