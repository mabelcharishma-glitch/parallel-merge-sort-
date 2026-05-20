# parallel-merge-sort-
Parallel Merge Sort in C using threads

# Parallel Merge Sort in C

## Overview

This project implements Parallel Merge Sort using threads in C language. The algorithm uses divide-and-conquer along with parallel processing to improve sorting efficiency.



## Features

- Multi-threaded sorting
- Faster execution for large datasets
- Divide and Conquer approach
- Efficient merging process



## Technologies Used

- C Language
- POSIX Threads (pthreads)
- VS Code


## Algorithm Used

Parallel Merge Sort divides the array into smaller subarrays and sorts them simultaneously using multiple threads.



## Time Complexity

| Parallel Merge Sort | O((n log n)/p + log n) |

Where:
- n = number of elements
- p = number of processors


## Sample Input

6
4500 1200 7800 3000 2500 9000


## Sample Output

1200 2500 3000 4500 7800 9000


## Advantages

- Faster than traditional Merge Sort
- Utilizes multi-core processors
- Suitable for large-scale data processing

