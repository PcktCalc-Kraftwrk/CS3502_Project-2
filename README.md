# About
CS 3502: Project 2 - CPU Scheduling

This project was built off of https://github.com/FrancisNweke/CPU-Simulator-GUI and requires Virtual Studio. It is meant as an expansion which adds HRRN and SRTF algorithms to the simulator.

# Highest Response Ratio Next
Takes in the arrival and burst time stated by the user for each process and adds those values to the corresponding array. It then moves through each array and calcuates the wait times and response ratio of each process, once again adding those values to related arrays. If the ratio is lower than the current max, the current process is sent to the front of the available processes. Once the processes are sorted in the proper order, the current wait and turnaround times are created and printed, then the current process is considered finished. This loops until the method has gone through every process in every order. Finally, the averages of the wait time and turnaround time is presented
![image](https://github.com/user-attachments/assets/e4fc0647-bec2-44e3-a5b8-0e56565ede50)
![image](https://github.com/user-attachments/assets/ac8ec58c-81f3-457b-9140-ff5683b8064d)

# Shortest Remaining Time First
