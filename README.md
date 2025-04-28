# About
CS 3502: Project 2 - CPU Scheduling

This project was forked from https://github.com/FrancisNweke/CPU-Simulator-GUI and requires Virtual Studio. It is meant as an expansion which adds HRRN and SRTF algorithms to the simulator. If you encounter any issues, then download from him and modify it with my additions.

# Highest Response Ratio Next
Takes in the arrival and burst time stated by the user for each process and adds those values to the corresponding array. It then moves through each array and calcuates the wait times and response ratio of each process, once again adding those values to related arrays. If the ratio is lower than the current max, the current process is sent to the front of the available processes. Once the processes are sorted in the proper order, the current wait and turnaround times are created and printed, then the current process is considered finished. This loops until the method has gone through every process in every order. Finally, the averages of the wait time and turnaround time is presented
![image](https://github.com/user-attachments/assets/e4fc0647-bec2-44e3-a5b8-0e56565ede50)
![image](https://github.com/user-attachments/assets/ac8ec58c-81f3-457b-9140-ff5683b8064d)

# Shortest Remaining Time First
The same general principle as HRRN when it comes to its general structure. The biggest difference is that while each process is being analyzed, if the next process arrived while the current process is running and its leftover time is less than the burst of the current process, the next process is sent up-front. Everything else, from inputing arrival times to showing the waiting times, is basically unchanged.
![image](https://github.com/user-attachments/assets/aca9be2e-f9c7-43cb-bf52-24f2ffd56fd0)
