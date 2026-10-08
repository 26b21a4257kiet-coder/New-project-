# New-project-🏭 Factory Production Planner (A7)

Mathematics Mini Project — ABHIYAN

A Python-based mathematical project that uses linear algebra, consistency, and rank analysis to help a factory determine production quantities and identify machine bottlenecks.

---

📌 Problem Statement

A factory makes 3 products using 3 machines. Each machine has limited working hours, and each product requires different amounts of time on each machine.

The project sets up the problem as a system of linear equations, finds the production quantities, checks whether the system is consistent, and identifies the bottleneck machine when the system cannot be satisfied.

---

🎯 Objectives

- Convert a real-world factory problem into a mathematical model.
- Represent the system using matrices and vectors.
- Check the consistency of the system.
- Perform rank analysis.
- Calculate the production quantities.
- Verify the obtained solution.
- Identify the bottleneck machine.
- Display the results using tables and visualizations.

---

🧮 Mathematical Concepts

1. Consistency

Consistency determines whether the system of equations has a valid solution.

For a system:

AX = B

the system is consistent when:

Rank(A) = Rank([A | B])

---

2. Rank Analysis

The rank of a matrix helps determine the number of independent equations and whether a unique solution exists.

The project compares:

- Rank of coefficient matrix "A"
- Rank of augmented matrix "[A | B]"

---

3. Practical Interpretation

The mathematical solution is converted into a real-world factory interpretation.

For example:

- Product 1 → "x₁" units
- Product 2 → "x₂" units
- Product 3 → "x₃" units

The values are then checked against machine-hour limitations.

---

⚙️ Mathematical Model

Let:

- "x₁" = quantity of Product 1
- "x₂" = quantity of Product 2
- "x₃" = quantity of Product 3

The factory problem can be represented as:

A X = B

where:

A = Machine/Product time matrix
X = Production quantity vector
B = Available machine hours

For example:

[a₁₁  a₁₂  a₁₃] [x₁]   [b₁]
[a₂₁  a₂₂  a₂₃] [x₂] = [b₂]
[a₃₁  a₃₂  a₃₃] [x₃]   [b₃]

---

🔄 Methodology

The project follows these steps:

Input Factory Data
        ↓
Create Matrix A and Vector B
        ↓
Construct AX = B
        ↓
Check Consistency
        ↓
Calculate Matrix Ranks
        ↓
Find Production Quantities
        ↓
Verify Solution
        ↓
Identify Bottleneck
        ↓
Generate Tables & Charts

---

🧑‍💻 Technology Used

Technology| Purpose
Python| Main programming language
Google Colab| Development environment
NumPy| Numerical and matrix calculations
SymPy| Symbolic mathematics and rank analysis
Matplotlib| Data visualization

---

📊 Features

- Dynamic factory input
- Matrix-based mathematical model
- Consistency checking
- Rank analysis
- Production quantity calculation
- Solution verification
- Bottleneck identification
- Machine utilization analysis
- Graphical visualization
- Beginner-friendly Python implementation

---

📈 Results

The project generates:

- Production quantity for each product
- Rank of coefficient matrix
- Rank of augmented matrix
- Consistency status
- Machine utilization
- Bottleneck information
- Visual charts for easier interpretation

Example output:

Factory Production Planner
--------------------------

Product 1 Quantity : ...
Product 2 Quantity : ...
Product 3 Quantity : ...

Rank(A)       : ...
Rank([A | B]) : ...

System Status : Consistent

Bottleneck Machine : Machine 2

---

🚧 Limitations & Assumptions

- Linear relationships are assumed.
- Input data is assumed to be accurate.
- Machine capacities are treated as fixed.
- Product requirements are assumed to remain constant.
- The basic model does not include changing production costs or demand.
- Boundary conditions depend on the supplied input values.

---

🌱 Future Scope

The project can be extended with:

- Real-time factory data integration
- Cloud API integration
- Production cost optimization
- Demand-based production planning
- Multi-objective optimization
- Machine scheduling
- AI/ML-based production forecasting
- Real-time dashboard
- Multiple factories and machines

---

🌍 Real-World Application

The same mathematical approach can be applied to many manufacturing environments, from large industrial plants to small bakeries.

It can help understand:

- Machine capacity
- Production planning
- Resource utilization
- Production constraints
- Bottleneck identification

---

📸 Proof of Work

Day 1 — Setup

- Google Colab setup
- Python environment
- Hello World execution

Day 2 — MVP

- Initial AI-assisted code
- Basic mathematical model
- Initial output

Day 3 — Custom Analysis

- Consistency analysis
- Rank analysis
- Bottleneck identification
- Custom visualizations

---

👥 Team Information

Team Name: "[Your Team Name]"

Leader: "[Leader Name & Roll No]"

Members:

- "[Member 1 Name & Roll No]"
- "[Member 2 Name & Roll No]"
- "[Member 3 Name & Roll No]"

---

▶️ How to Run

Option 1 — Google Colab

1. Open the project in Google Colab.
2. Copy the Python code into a new notebook.
3. Install/import the required libraries.
4. Enter the factory data.
5. Run the code.
6. View the mathematical analysis, production quantities, and charts.

Option 2 — Local Python

Install the required libraries:

pip install numpy sympy matplotlib

Then run the Python program:

python factory_production_planner.py

---

📁 Project Structure

Factory-Production-Planner/
│
├── README.md
├── factory_production_planner.py
├── Factory_Production_Planner.ipynb
│
├── screenshots/
│   ├── day1_setup.png
│   ├── day2_mvp.png
│   └── day3_analysis.png
│
└── results/
    └── charts/

---

📜 Conclusion

Factory Production Planner (A7) demonstrates how mathematical concepts such as linear equations, matrices, consistency, and rank analysis can be applied to a practical manufacturing problem.

The project connects B.Tech Mathematics with real-world production planning, making mathematical analysis easier to understand through Python and visualization.

---

🎓 Mathematics + Python + Real-World Manufacturing

Factory Production Planner (A7) — ABHIYAN
