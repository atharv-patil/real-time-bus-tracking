# Real-time Bus Tracking Visualization

This project aims to visualize real-time bus tracking using the [Open Transit Data API](https://opendata.iiitd.edu.in/) provided by the Delhi Government. It retrieves the current positions of public buses using the API and creates a video visualization to showcase the dynamic movements and scale of the transit system in Delhi. By fetching the data using the API, the Python code converts it into a JSON format and extracts the latitude and longitude coordinates of the buses. The Folium library is then used to create a map centered around New Delhi, where small red circle markers are added to represent the bus locations. The resulting map is saved as an HTML file.

To enhance the visualization, the HTML files are converted to PNG images using the Html2Image library. These images are then combined to create a video representation of the bus movements over time. The resulting video provides an engaging view of the bustling transit system in Delhi, showcasing the extensive network of buses and their movements during the day.

### YouTube Video

To see the real-time bus tracking visualization in action, check out the following video:

[![Real-time Bus Tracking on OpenStreetMap](https://img.youtube.com/vi/BjVXcSRAMr8/0.jpg)](https://www.youtube.com/watch?v=BjVXcSRAMr8)

Click on the image to watch the video or [click here](https://www.youtube.com/watch?v=BjVXcSRAMr8) to open it in a new tab.

#### The code was running for well over 6 hours for getting all the html files
![image](https://github.com/atharv-patil/real-time-bus-tracking/assets/83455141/24919dbe-e788-4776-8b94-fdfa738f48ef)


### Technologies Used

The project utilizes the following technologies:

- `python3`: The programming language used for the implementation.
- `gtfs-realtime-bindings`: A library to handle GTFS-realtime data in Python.
- `requests`: A library for making HTTP requests to fetch data from the API.
- `folium`: A Python library for creating interactive maps and adding markers to represent bus locations.
- `geopy`: A library for geocoding and retrieving location details.
- `json`: A built-in Python library for working with JSON data.
- `time`: A built-in Python library for time-related functions.
- `os`: A built-in Python library for interacting with the operating system.
- `html2image`: A library to convert HTML files to images.
- `cv2` (OpenCV): A library for image and video processing.

Please refer to the code and instructions provided in the repository to set up and run the project. Feel free to customize and enhance the project based on your specific requirements and preferences.
