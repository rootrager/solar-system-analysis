Solar System Analysis Project
Overview
This project analyzes the planets of our Solar System to determine their suitability for human life and landing. Using real data from the "Solar System Dataset", we evaluate parameters like gravity, temperature, and atmospheric composition to find livable planets. The project combines programming (Python) with physics to create an interactive tool for space exploration.
Features

Data Analysis: Loads and processes real Solar System data from planets_updated.csv.
Visualization: Generates plots for gravity and temperature.
Object-Oriented Programming: Uses a SpacePlanet class to analyze planets.
GUI: Interactive interface with Tkinter to explore planets.
Output: Saves results of livable planets to safe_planets.csv.

Requirements

Python 3.x
Libraries: pandas, matplotlib, seaborn, tkinter

How to Run

Clone the repository:git clone https://github.com/your-username/solar-system-analysis.git


Install dependencies:pip install pandas matplotlib seaborn


Run the script:python solar_system.py


Enter a planet name in the GUI to see its report.

Results

Livable Planets: Based on the criteria (gravity 5-15 m/s², temperature -50 to 50°C, breathable atmosphere), only Earth is suitable.
Plots: Check gravity_plot.png and temperature_plot.png for visualizations.

A Brief Article on the Solar System and the Intersection of Programming and Physics
The Solar System: A Quick Overview
The Solar System consists of eight planets orbiting the Sun: Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune. Each planet has unique physical characteristics:

Gravity: Varies from 3.7 m/s² on Mercury and Mars to 23.1 m/s² on Jupiter.
Temperature: Ranges from 464°C on Venus to -200°C on Neptune.
Atmosphere: Earth is the only planet with a breathable atmosphere (78.1% Nitrogen, 20.9% Oxygen).

These characteristics determine a planet's suitability for human life. For example, Earth’s gravity (9.8 m/s²) and temperature (15°C) are ideal, while Venus’s extreme heat (464°C) and high pressure (92 bars) make it uninhabitable.
Combining Programming and Physics
This project demonstrates how programming and physics can work together to solve real-world problems:

Physics: We use concepts like gravity (F = m * g) to calculate landing forces and evaluate livability based on physical parameters.
Programming: Python libraries like pandas and seaborn help us process data and visualize trends, while tkinter creates an interactive interface.

By merging these fields, we can simulate space missions, analyze data, and make informed decisions about planetary exploration.
Why This Matters
Understanding the Solar System through data analysis helps us plan future space missions. Programming allows us to automate complex calculations, while physics provides the scientific foundation. Together, they enable us to explore the universe in ways that were once unimaginable.
License
This project is licensed under the MIT License.

