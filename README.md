# RTS Scheduling Algorithm Repository
Welcome to the RTS Scheduling Algorithm repository! This repository contains implementations of several Real-Time Scheduling (RTS) algorithms along with a task generator.
<br>
# Real-Time Scheduling Algorithms Implemented:

## Rate Monotonic Scheduling (RMS):
-> RMS is a priority-based preemptive scheduling algorithm.
-> Tasks are assigned priorities based on their periods, with shorter period tasks having higher priorities.
-> It's optimal for periodic tasks with known periods and fixed execution times.

## Deadline Monotonic Scheduling (DMS):
-> DMS is another priority-based preemptive scheduling algorithm.
-> Priorities are assigned based on deadlines, with tasks having closer deadlines getting higher priorities.
-> It ensures meeting task deadlines by prioritizing tasks with closer deadlines.

## Least Slack Time Scheduling (LST):
-> LST is a dynamic priority scheduling algorithm.
-> Priorities are assigned based on the slack time, which is the difference between a task's deadline and its completion time.
-> Tasks with less slack time are given higher priorities, aiming to minimize the maximum lateness.

## Earliest Deadline First (EDF):
-> EDF is a dynamic priority scheduling algorithm.
-> Priorities are assigned based on the absolute deadline, with tasks having earlier deadlines getting higher priorities.
-> It guarantees meeting deadlines if the system is schedulable.

## Task Generator:
A task generator is provided to create synthetic task sets for testing the implemented scheduling algorithms. It generates tasks with parameters such as periods, execution times, and deadlines.

## Notebooks:
The repository includes separate Jupyter notebooks for each implemented algorithm. These notebooks demonstrate how each algorithm works and provide examples of task scheduling scenarios.

<br>

# How to Use:
-> Clone the repository to your local machine.
-> Ensure you have Python and Jupyter Notebook installed.
-> Open the desired notebook (RMS.ipynb, DMS.ipynb, LST.ipynb, EDF.ipynb) in Jupyter Notebook.
-> Follow the instructions provided within each notebook to run examples and understand the algorithms.
-> Utilize the task generator to create custom task sets for testing.
<br>

# Contributions:
Contributions to this repository are welcome! If you have improvements, bug fixes, or additional algorithms to suggest, feel free to fork the repository and submit a pull request.
<br>

# Disclaimer:
These implementations are for educational purposes and may not be suitable for deployment in real-time systems without thorough testing and validation.

_________________________________________________________________

For any questions or concerns, please don't hesitate to reach out.
Happy scheduling! 🕒
