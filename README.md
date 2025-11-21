Project Overview

This mini-project demonstrates how different algorithmic strategies can be applied to solve real-world problems effectively.
The project focuses on four problem scenarios, each using a different type of algorithmic approach:

Problem	Domain	Strategy
TV Commercial Scheduling	Media & Advertisement	Greedy
Budget Maximization	Finance & Planning	Dynamic Programming (0/1 Knapsack)
Sudoku Puzzle Solver	Gaming	Backtracking
Password Cracking	Cybersecurity	Brute Force

The notebook includes full implementations, profiling, visualization, and performance analysis.

Algorithms Implemented
Strategy	Characteristics	Applied To
Greedy	Makes best choice at each step	Select profitable commercials
Dynamic Programming	Optimal substructure + overlapping subproblems	0/1 Knapsack for budget profit maximization
Backtracking	Try–undo–retry recursive approach	Sudoku completion
Brute Force	Try every possible solution	Password cracking

Performance Profiling & Visualization

For each problem, the notebook provides:

✔ Execution time measurement using time.perf_counter
✔ Graphs via matplotlib showing how performance changes with input size

Visualization	X-Axis	Y-Axis
Job Sequencing	Number of ads	Total revenue
Knapsack	Budget capacity	Maximum profit
Sudoku	Number of blank cells	Time taken
Password Cracking	Password length	Time taken

These results help compare how algorithms scale in real execution, not just theoretical complexity.

 Key Insights

🔹 Greedy algorithm selects commercials efficiently and revenue increases with more ad options
🔹 0/1 Knapsack DP supports informed budget planning through maximized value under constraint
🔹 Sudoku Backtracking becomes computationally expensive as blank cells increase
🔹 Brute-Force password cracking grows exponentially — impractical for security-level passwords

 Repository Structure (recommended)
algo-strategies-mini-project-<yourname>/
│
├── algo_strategies_notebook.ipynb
├── README.md
├── requirements.txt
├── images/ (optional — for exported plots)
└── .gitignore

 How to Run the Notebook
Install dependencies
pip install -r requirements.txt

 Launch Jupyter Notebook
jupyter notebook algo_strategies_notebook.ipynb


The notebook runs independently — no external datasets are required.

 References / Suggested Reading

CLRS – Introduction to Algorithms

Python documentation for time, matplotlib, itertools

Memory & time profiling tutorials for Python

 Acknowledgement

This project is developed as part of Design and Analysis of Algorithms Lab (ENCA351)
at School of Engineering and Technology, K.R. Mangalam University.

🎉 README COMPLETE

