# Weather-Prediction
This web application provides real-time weather monitoring and safety information for coastal areas of Tamil Nadu, India. It's designed specifically for fishermen, marine operators, and coastal residents who need accurate weather data for safety and planning purposes.
# Key-Features
Comprehensive Coverage:
Includes all 38 districts of Tamil Nadu with accurate coordinates
Displays real-time weather data for each location

Interactive Map:
Color-coded temperature markers (red for hot, blue for cool, etc.)
Clickable markers with detailed weather popups
Zoom to location when clicked from sidebar

Weather Dashboard:
Sidebar with all districts and current weather conditions
Temperature, humidity, wind speed, and weather condition for each location
Visual weather icons (sun, clouds, rain, etc.)

Search Functionality:
Quickly find any district by name
Filters the sidebar list in real-time

Visual Design:
Clean, responsive layout that works on all devices
Temperature legend for easy interpretation
Smooth animations and transitions

Performance:
Loads all weather data simultaneously using Promise.all()
Shows loading spinner during data fetch
Error handling for failed API requests
