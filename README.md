CPU Scheduling Algorithms Simulator
====================================

DESCRIPTION
-----------
This project simulates CPU scheduling algorithms, including:
- **Round Robin (RR)**
- **Shortest Job Next (SJN)**
- **Priority Non-Preemptive**
- **Shortest Remaining Time (SRT)**

It generates a Gantt chart to visualize the execution of processes and calculates key metrics such as waiting time, turnaround time, and completion time for each process.

FEATURES
--------
- Implementations of various CPU scheduling algorithms
- Gantt chart visualization for process execution
- Calculation of process metrics (waiting time, turnaround time, etc.)
- Interactive input for process data (arrival time, burst time, priority)

HOW TO RUN
-----------
1. Ensure Python and necessary libraries are installed (e.g., **IPython**, **JSON**).
2. Run the script in a Python environment or Jupyter notebook.
3. Input the process data (arrival time, burst time, priority) and select the desired algorithm.
4. The program will display the Gantt chart and metrics for the selected algorithm.

KEY FILES
---------
- **os_assignment_group1.py**: Main Python script for simulating CPU scheduling algorithms.
- **Input processing**: Collects process data and runs the selected scheduling algorithm.
- **Gantt chart generation**: Visualizes the execution of processes.

REQUIREMENTS
------------
- Python 3.x
- Required Python libraries: `IPython`, `JSON`

