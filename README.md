**Weather Application**

**Project Overview**

The MDAH Weather Application is a desktop-based utility designed to
provide users with comprehensive, real-time weather information.
Developed as a Data Structures and Algorithms (DSA) final project, it
integrates core programming concepts like Linked Lists and Sorting
Algorithms with modern API connectivity and File I/O operations.

**Core Features**

Real-time Weather Updates: Fetches live temperature, pressure, and
weather conditions using the OpenWeatherMap API.

Dynamic Search History: Maintains a list of searched cities,
automatically organized using the Insertion Sort algorithm.

Geographic Coordinates: Utilizes a local city_coordinates.csv file to
provide precise Latitude and Longitude for selected cities.

Data Persistence: Automatically logs every search, including weather
details and timestamps, into a local text file (New Text Document.txt).

Interactive UI: Features a turquoise-themed Tkinter interface with
autocomplete comboboxes and a scrollable data display area.

Visual Data Representation: Includes a built-in graph generation feature
to visualize the relationship between temperature and pressure for
searched cities.

**Technical Specifications**

Programming Language: Python 3.x serves as the core language for logic
and integration.

GUI Framework: Tkinter is used to build the desktop interface and handle
user interactions.

Data Structure: A Custom Singly Linked List is implemented to manage and
store city data efficiently.

Sorting Algorithm: Insertion Sort is utilized to organize and display
the user\'s search history.

API Integration: OpenWeatherMap API is integrated to fetch real-time
weather data via JSON parsing.

File Handling: The system uses CSV files to store geographic coordinates
and **TXT files** for persistent search history logging.

**Project Structure**

DSA FINAL.py: The main application logic, including the GUI setup, API
calls, and DSA implementations.

city_coordinates.csv: A dataset containing geographical data for various
cities across Pakistan.

New Text Document.txt: A persistent log file that stores a history of
weather queries with exact date and time stamps.

**How to Use**

Search: Select a city from the dropdown or type a name into the search
bar.

Fetch: Click the \"Done\" button to retrieve live weather data and
coordinates.

Visualize: Use the \"Display Graph\" button to see a plot of your search
results.

Review: Click \"Access Stored Data\" to view your search history
directly within the app.
