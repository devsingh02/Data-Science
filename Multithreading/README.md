# Multithreading-matrix-multiplication
## Overview

This Python script benchmarks the performance of matrix multiplication using multi-threading. It generates 100 random matrices of size 5000x5000 and multiplies each of them with a constant matrix of the same size. The performance is measured for different numbers of threads ranging from 1 to 8.

## Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- Pandas
- psutil

The script will generate the following outputs:
    - Table showing the time taken for matrix multiplication with different numbers of threads.
    - Graph plotting the matrix multiplication time versus the number of threads.
    - CPU usages (if available).
    
## Results Interpretation

- **Time Taken (Sec):** Indicates the time taken for matrix multiplication in seconds. Lower values indicate better performance.
- **Number of Threads:** The number of threads used for matrix multiplication. Higher values may improve performance up to a certain point, depending on the system's capabilities.
- **CPU Usage:** Percentage of CPU being used.

## Result DataFrame

| Threads | Time Taken (Sec) | CPU Usage (%) |
|---------|------------------|---------------|
| 1       | 8.741642	     |   15.6%       |
| 2	      |  8.724550	     |   98.8%       |
| 3	      |  7.733741	     |   98.6%       |
| 4	      |  8.779428	     |   98.9%       |
| 5	      |  11.439377	     |   100.0%      |
| 6	      |  9.078620	     |   99.0%       |
| 7	      |  9.017452	     |   98.4%       |
| 8	      |  8.783360	     |   98.6%       |
