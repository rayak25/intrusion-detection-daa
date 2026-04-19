# Intrusion Detection using String Matching Algorithms (DAA Project)

This project implements a web-based intrusion detection system that identifies malicious patterns in network data using classical string matching algorithms. It focuses on demonstrating algorithmic efficiency and comparative analysis as part of Design and Analysis of Algorithms (DAA).

##  Features

- Detection of attack patterns (e.g., SQL injection, XSS) in input data
- Implementation of:
  - Naive String Matching
  - Knuth-Morris-Pratt (KMP)
  - Rabin-Karp
- Performance comparison (execution time, matches found)
- Visualization of:
  - KMP (LPS array construction)
  - Rabin-Karp (rolling hash mechanism)
- Graphical analysis of input size vs execution time
- Clean web interface for interactive testing

## Algorithms Used

### 1. Naive String Matching
Checks for pattern occurrence by brute-force comparison.  
Time Complexity: O(nm)

### 2. Knuth-Morris-Pratt (KMP)
Uses LPS (Longest Prefix Suffix) array to avoid redundant comparisons.  
Time Complexity: O(n + m)

### 3. Rabin-Karp
Uses hashing and rolling hash technique for efficient matching.  
Average Time Complexity: O(n + m)

##  Performance Analysis

The system compares:
- Execution time (in milliseconds)
- Number of matches detected
- Behavior with increasing input size

Results are visualized using graphs to highlight differences between algorithms.

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Python (Flask)
- Visualization: Matplotlib / Chart.js

##  Project Structure
project/
│── app.py
│── algorithms/
│ ├── naive.py
│ ├── kmp.py
│ ├── rabin_karp.py
│── templates/
│ ├── index.html
│── static/
│ ├── style.css
│── data/
│ ├── sample_inputs.txt


##  Conclusion

KMP performs more efficiently than the naive approach by eliminating redundant comparisons, while Rabin-Karp provides efficient average-case performance using hashing. The project demonstrates how classical DAA techniques can be applied to real-world security problems.

##  Future Improvements

- Integration with real-time packet capture
- Addition of Boyer-Moore algorithm
- Enhanced visualization and analytics dashboard

## Author

Ramya   
B.Tech CSE – DAA Project
