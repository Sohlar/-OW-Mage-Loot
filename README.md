This list is not perfect, but is a good benchmark for decision making.

WoW Classic Mage Gear Simulator
Overview
This project is a gear simulator and performance tracker for World of Warcraft Classic mages. It helps analyze and compare gear options across different raids and characters, while also tracking raid attendance and performance metrics.
Files
CSV Files
1. dougie_gearsim.csv, yinnifer_gearsim.csv, freeze_gearsim.csv, phus_gearsim.csv, icyhot_gearsim.csv, dmoney_gearsim.csv:
These files contain gear data for individual mages. Each file represents a specific character's gear options.
AQ40_10_22_24.csv, BWL_10_22_24.csv, MC_10_22_24.csv:
These files contain gear data from specific raids:
AQ40: Ahn'Qiraj
BWL: Blackwing Lair
MC: Molten Core
Python Script
main.py: The main Python script that processes raid logs, calculates attendance, and retrieves performance metrics.
What the CSVs Do
The CSV files serve two main purposes:
1. Individual Mage Gear Data (e.g., dougie_gearsim.csv):
Contains all potential gear pieces for a specific mage
Includes item details such as name, slot, source, stats, and spell power gain
Allows for individual analysis of gear options
Raid-Specific Gear Data (e.g., AQ40_10_22_24.csv):
Compiles gear data from specific raids
Allows for comparison of items across different characters
Includes effective spell power gain calculations
These files enable players to:
Compare gear across different characters and raids
Analyze the best gear options for each slot
Make informed decisions about which items to pursue for maximizing spell power
How the System Works
1. Gear Simulation:
The individual mage CSV files contain all potential gear pieces for each character.
The raid-specific CSV files compile this data, allowing for easy comparison across characters.
Performance Tracking:
The main.py script processes raid logs to track attendance and performance metrics.
It uses web scraping to retrieve data from online logs.
Attendance is calculated based on raid participation.
Performance metrics are retrieved for Molten Core (MC) and Blackwing Lair (BWL) raids.
Data Output:
The script generates an ow_sheet.csv file containing:
Mage names
Raid attendance
Performance metrics for MC and BWL
Overall performance calculation
How to Use
Ensure you have Python installed on your computer.
Place all CSV files and the main.py script in the same directory.
Install required Python libraries (selenium, pandas).
Run the main.py script to process raid logs and generate performance data.
Use the generated ow_sheet.csv and raid-specific CSVs to analyze gear options and player performance.
This tool helps World of Warcraft Classic mage players optimize their gear choices and track raid performance without needing to understand complex game mechanics or perform manual calculations.
