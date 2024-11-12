# **Climate Analysis and Flask API**

This project analyzes climate data from Hawaii using Python and SQLAlchemy and provides a Flask API to query the processed data. The API allows users to access precipitation data, station information, and temperature statistics over specified time ranges.

---

## **Project Structure**
The project includes the following files:

- **`hawaii.sqlite`**: SQLite database containing climate data.
- **`app.py`**: Flask application code implementing the API.
- **`climate_starter.ipynb`**: Jupyter Notebook for initial data exploration and query design.
- **`hawaii_measurements.csv`**: Climate measurements dataset.
- **`hawaii_stations.csv`**: Station information dataset.

---

## **Technologies Used**
- **Python**: For data analysis and backend logic.
- **Flask**: For creating RESTful API routes.
- **SQLAlchemy**: For database interactions.
- **Matplotlib**: For plotting visualizations.
- **Pandas**: For data manipulation.
- **SQLite**: For storing and querying the climate data.

---

## **How to Run**

### **Step 1: Set Up the Environment**
1. Install Python (preferably version 3.10 or later).
2. Install the required Python libraries:
```bash
pip install flask sqlalchemy matplotlib pandas

### Step 2: Run the Flask Application

Navigate to the directory containing `app.ipynb`.

#### Start the Flask server:
```bash
python app.ipynb
```
##### Access the API in your browser or API client (e.g., Postman) at: http://127.0.0.1:5000

##### API Endpoints
######
Description: Lists all available routes.  
Response:
```plaintext
Welcome to the Climate App API!
Available Routes:
- /api/v1.0/precipitation
- /api/v1.0/stations
- /api/v1.0/tobs
- /api/v1.0/<start>
- /api/v1.0/<start>/<end>
```

## **Visualizations**

The `climate_starter.ipynb` notebook contains visualizations for:

1. Precipitation over the Last 12 Months:
   - Line plot of precipitation data.

2. Temperature Observations Histogram:
   - Histogram of temperature observations for the most active station.




   
