# Project--03
# Mall Customer Segmentation & Streamlit Application
## Overview
[Brief description of the project]
## Dataset
- File: Mall_Customers.csv
- Total samples: [number]
- Clustering features:
- Annual Income (k$)
- Spending Score (1-100)
## Method
1. Scale the clustering features with StandardScaler.
2. Compare several K values using the Elbow Method.
3. Run K-Means using the K selected in the Streamlit app.
4. Visualize the resulting customer clusters.
## Streamlit Application
**Live App:** [your Streamlit URL]
### Screenshot
![Streamlit Application](screenshots/streamlit_app.png)
## Installation
git clone [your-repo-url]
cd mall-customer-segmentation
pip install -r requirements.txt
## Usage
streamlit run app.py
## Project Structure
mall-customer-segmentation/
|-- data/
| ‘-- Mall_Customers.csv
|-- app.py
|-- screenshots/
| ‘-- streamlit_app.png
|-- README.md
‘-- requirements.txt
## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Streamlit


