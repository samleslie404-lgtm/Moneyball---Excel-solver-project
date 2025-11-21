# Moneyball---Excel-solver-project
This project applies optimization techniques to build an efficient baseball roster using Moneyball principles. The goal is to 
maximize WAR (Wins Above Replacement) while meeting several real-world constraints such as salary limits, position requirements, 
and player characteristics.

#       >>Project Overview:

The model uses the Excel Solver tool to determine the optimal combination of players based on performance and cost. 
Both GRG Nonlinear and Simplex LP methods were tested to evaluate model behavior under different optimization approaches.

The dataset includes player salaries, WAR values, batting averages, and position information. Binary decision variables 
(1 = selected, 0 = not selected) allow Solver to construct a valid team that adheres to all constraints.

#        >>Key Constraints

The optimization model incorporates multiple realistic roster rules, including:

 - $220 million Salary cap limit

 - Requirements on number of players per position

 - Minimum 3 Canadian players

 - At least 3 players with a batting average above 0.300

 - Roster size of 15

These constraints ensure the resulting roster is both valid and competitive.

#          >>What This Project Demonstrates
1. Understanding of Solver and Optimization Logic
 - Built and tested both GRG Nonlinear and Simplex LP approaches
 - Designed a clear objective function to maximize team WAR
 - Implemented logical constraints to guide Solver’s feasible solutions

2. Model Testing & Scenario Evaluation
 - Compared Solver methods to evaluate consistency
 - Adjusted constraints and observed changes in roster output
 - Verified model stability and decision logic

3. Strong Excel Data Analysis Skills
 - Extensive use of cell referencing for reproducible calculations across a large dataset
 - Leveraged conditional formatting to flag key players and create clean summary sheets
 - Structured formulas to automate totals, averages, and constraint checks
 - Created a workflow that makes the sheet easy to understand, modify, and extend

#            >>Why This Project Matters

This assignment highlights the ability to use Excel not only for analysis but for decision optimization—a key skill in 
analytics-driven roles. The project shows capability in:

 - Building quantitative decision models
 - Translating real-world constraints into mathematical logic
 - Using structured spreadsheets for reproducible, scalable analysis
 - Communicating data insights through clear summaries and formatting
