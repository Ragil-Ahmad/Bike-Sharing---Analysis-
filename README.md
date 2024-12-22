# Bike-Sharing Dashboard Analysis
As final delivere for certification "Analisis Data Dengan Python"

## Setup Environment - Python

```python
py -m venv .venv
.\.venv\Scripts\activate
pip freeze >  requirements.txt
```

## Different Path Dataset In Deploy and Local
I'm using different path for dataset when deploy in cloud and local
### Local
```python
day_df = pd.read_csv("day_clean_data.csv")
hour_df = pd.read_csv("hour_clean_data.csv")
```
### Deploy
```python
day_df = pd.read_csv("dashboard/day_clean_data.csv")
hour_df = pd.read_csv("dashboard/hour_clean_data.csv")
```
## Run streamlit app
```python
streamlit run dashboard/dashboard.py
```
