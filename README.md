# API_INTEGRATION_AND_DATA_VISUALIZATION_TASK1
COMPANY : CODTECH IT SOLUTONS
NAME : SAKSHI SALUNKHE
INTERN ID : CT04DF2845
DOMIAN : PYTHON PROGRAMMING
DURATION : 4 WEEKS
MENTOR : NEELA SANTOSH KUMAR
DESCRIPTION OF TASK : [Internship_Task1_WeatherForecast.pdf](https://github.com/user-attachments/files/20673268/Internship_Task1_WeatherForecast.pdf)
Internship Task 1 - Weather Forecast Visualization
Project Title:
Weather Forecast Data Visualization using OpenWeatherMap API in Python
Objective:
To develop a Python application that fetches real-time weather forecast data for a city (Mumbai)
using the OpenWeatherMap API and visualizes the temperature trends for the next 5 days using a
line graph.
Technologies Used:
- Programming Language: Python
- API Provider: OpenWeatherMap
- Libraries: requests, matplotlib, datetime
Folder Structure:
task1-weather-forecast/
 task1.py
 TASK1_OUTPUT.jpg
 weather_forecast_chart.png
 README.md
Setup Instructions:
1. Install Python 3.x
2. Install libraries:
 pip install requests matplotlib
3. Replace the API key in task1.py
4. Run the script.
Code Breakdown:
- Import Libraries: requests, matplotlib.pyplot, datetime
- API Setup with key and city (Mumbai)
- Fetch data using requests.get()
- Extract temperature and datetime
- Plot the data using matplotlib
- Save and display the chart
Output:
The chart shows temperature (C) vs. date & time (3-hour intervals) over 5 days for Mumbai.
Saved as weather_forecast_chart.png and displayed using plt.show()
Learning Outcomes:
- REST API usage
- JSON data extraction
- Datetime processing in Python
- Plotting time-series data using matplotlib
Enhancements:
- Add weather conditions (Rain, Sunny)
- Use icons or color codes
- Dynamic city input
- Save data to CSV
- Build a GUI or web app
Internship Task Checklist:
[x] API integration implemented
[x] Data extraction working
[x] Visualization generated and saved
[x] Output image created
[x] Task ready for submission
Sample GitHub README:
# Weather Forecast Visualization using OpenWeatherMap API
This Python script fetches 5-day weather forecast data for Mumbai and visualizes it using a line
chart.
Features:
- OpenWeatherMap 5-day forecast API
- Temperature plotted every 3 hours
- Output saved as image
Requirements:
- Python 3.x
- matplotlib
- requests
How to Run:
1. Replace API key in task1.py
2. Run python task1.py
3. Output saved as weather_forecast_chart.png
Conclusion:
This project shows end-to-end implementation of an API-driven data visualization task using Python.
It demonstrates technical understanding and real-world data handling, ideal for internships or
resumes.
End of Document.
OUTPUT : ![Image](https://github.com/user-attachments/assets/2418e4eb-4454-4ade-ba41-8ad03cb48d86)
