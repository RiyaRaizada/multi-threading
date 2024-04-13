# multi-threading
Multithreading is the ability of a program or an operating system to enable more than one user at a time without requiring multiple copies of the program running on the computer. Multithreading can also handle multiple requests from the same user.

METHODOLOGY:
1. Libraries Used
numpy: Matrix operations.
multiprocessing.Pool and cpu_count: Utilize multiple CPU cores.
matplotlib.pyplot: Data visualization.
psutil: Monitor CPU usage.
2. Task Function
multiply_matrices(_)
3. Main Execution
task(num_matrices, num_threads): Performs multiprocessing task with specified number of matrices and threads. Measures start time, executes tasks in parallel, and calculates total time taken.
Iterates over a range of thread counts, records execution time, and plots a graph of threads vs. time taken.
Measures CPU usage for each thread count.


![image](https://github.com/RiyaRaizada/multi-threading/assets/88757064/1266569f-2d39-4412-b4f4-ac2f993c3849)

