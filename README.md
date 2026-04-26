Day 10 - Academic Data Drift & Copy Behavior Analyzer
Overview
In this project, I worked with student academic data to understand how data changes when copied and modified. The focus was on analyzing shallow copy and deep copy behavior along with detecting data drift. I also used NumPy and Pandas to perform statistical analysis on the data.
Objective
The goal of this project is to:
Generate student data using random values
Work with nested data structures
Apply shallow and deep copy
Modify copied data and observe changes
Perform statistical analysis using NumPy and Pandas
Detect data drift and classify system behavior
Data Structure
Each student record is stored as a dictionary with nested data.
Example:
student = {
"id": 1,
"marks": 75,
"attendance": 85,
"scores": [20, 18]
}
All student records are stored in a list.
Features
Generated random student data
Used list of dictionaries (nested structure)
Applied shallow copy and deep copy
Modified data using math functions (square root)
Updated scores and attendance
Converted data into Pandas DataFrame
Used NumPy for mean, median, and standard deviation
Calculated drift between original and modified data
Performed manual mean calculation
Classified results based on drift and copy behavior
Workflow
Generated student data randomly
Created shallow and deep copies
Applied mutations:
Increased marks using square root formula
Modified scores list
Updated attendance
Converted data into DataFrames
Calculated statistics using NumPy
Computed drift between original and modified data
Classified results based on conditions
Displayed all outputs clearly
Key Concepts
Shallow Copy:
It shares inner data structures. So, when changes are made, the original data may also get affected, leading to unintended modifications.
Deep Copy:
It creates a completely independent copy. Changes in copied data do not affect the original data.
Data Drift:
It refers to the change in statistical properties (like mean) of the data after modification.
Output
The program displays:
Original DataFrame
Shallow copy DataFrame
Deep copy DataFrame
Statistical values (mean, drift, standard deviation)
Tuple output (mean, drift, std_dev)
Final classification (Stable Data / Drift / Copy Failure)
Key Observation
Shallow copy caused unintended changes in the original data because it shares references.
Deep copy worked independently and did not affect the original data.
Drift value helped in understanding how much the data changed after mutation.
Learning Outcome
From this project, I learned how shallow and deep copy behave in complex data structures. I understood how to use NumPy and Pandas for data analysis. I also learned how to detect data drift and classify system behavior. This helped me understand real-world data processing and analysis concepts.
How to Run
Run the program using:
python3 DAY-10.py
Conclusion
Shallow copy can lead to data inconsistency due to shared references, while deep copy ensures safe and independent data handling. Data drift analysis helps in identifying changes in data patterns after modification.
