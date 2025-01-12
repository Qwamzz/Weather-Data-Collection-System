# Weather Data Collection System

## Project Overview

This project demonstrates the development of a weather data collection system by integrating various DevOps and cloud technologies. The system fetches real-time weather information from the OpenWeather API, processes the data, and securely stores it in AWS S3 for historical tracking. The project also emphasizes Python programming, infrastructure management, and automation.

![image](https://github.com/user-attachments/assets/b5c58d78-a2a9-4568-bf31-3251d11636ed)

## Key Features

- **Real-Time Weather Data:** Fetches current weather conditions for multiple cities.
- **Comprehensive Metrics:** Tracks temperature (°F), humidity, and weather descriptions.
- **Cloud Storage Integration:** Automatically stores weather data in AWS S3.
- **Multi-City Support:** Allows monitoring of multiple cities in a single run.
- **Timestamps:** Captures and stores data timestamps for easy historical analysis.

---

## Technical Overview

- **Programming Language:** Python 3.x
- **Cloud Provider:** AWS (S3)
- **API Integration:** OpenWeather API
- **Dependencies:**
  - `boto3`: AWS SDK for Python
  - `python-dotenv`: For managing environment variables
  - `requests`: For making API calls

---

## Project Structure

```plaintext
weather-dashboard/
  ├── src/
  │     ├── __init__.py
  │     └── weather_dashboard.py
  ├── tests/
  ├── data/
  ├── .env
  ├── .gitignore
  ├── requirements.txt
```

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Qwamzz/Weather-Data-Collection-System.git
cd 30days-weather-dashboard
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file in the project directory and add the following:

```plaintext
OPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name
```

### 4. Configure AWS Credentials

Set up AWS credentials using the AWS CLI:

```bash
aws configure
```

### 5. Run the Application

Execute the application to start collecting weather data:

```bash
python src/weather_dashboard.py
```

---

## Key Learnings

- **AWS S3:** Created and managed S3 buckets for storing weather data.
- **Environment Variables:** Used `.env` files for securely managing API keys and configurations.
- **Python Development:** Applied best practices for API integration and data handling.
- **Version Control:** Leveraged Git workflows for effective project development.
- **Error Handling:** Built robust error-handling mechanisms for distributed systems.
- **Cloud Management:** Managed resources and configurations in AWS.

---

## Future Enhancements

- **Weather Forecasting:** Extend functionality to include forecasts.
- **Data Visualization:** Build a dashboard to display weather trends.
- **City Expansion:** Add support for tracking additional cities.
- **Automated Testing:** Integrate unit and integration testing.
- **CI/CD Pipeline:** Set up continuous integration and delivery workflows.

---

## Placeholder for Images

- **System Architecture Diagram**
- **Sample Data Output**
- **AWS S3 Bucket Snapshot**
- **Error Logs Example**

---
