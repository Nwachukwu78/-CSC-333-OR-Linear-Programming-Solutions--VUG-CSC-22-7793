### **README.md for Linear Programming Project**

---

# **Linear Programming Project**

## **Project Description**
This project addresses a series of **Linear Programming (LP)** problems, each representing real-world scenarios involving optimization. These problems include maximizing profit, minimizing cost, and allocating limited resources effectively. Using Python and its libraries such as `SciPy`, `matplotlib`, and `NumPy`, the solutions are implemented programmatically and visualized graphically.

The project demonstrates:
1. Formulating optimization problems as mathematical models.
2. Solving them using Python's `scipy.optimize.linprog` method.
3. Visualizing constraints, feasible regions, and optimal solutions.

---

## **Objectives of the LP Problems**
### 1. **Maximizing Profit for a Factory**
**Goal**: Maximize the profit from producing two products (A and B) while adhering to resource constraints such as machine time and raw materials.

### 2. **Minimizing Cost for a Manufacturer**
**Goal**: Minimize the production cost of two products (X and Y) given limited labor and material resources.

### 3. **Other Problems**
Similarly, other problems deal with maximizing revenue, minimizing costs, and optimal resource allocation for different scenarios. The objectives are clearly stated in each respective code section.

---

## **How the Problems Were Solved**
1. **Mathematical Formulation**:
   - Define decision variables (e.g., \(x, y\) for the number of products or resources).
   - Create an objective function (e.g., profit = \(3x + 4y\)).
   - Establish constraints (e.g., \(2x + 3y \leq 12\)).

2. **Implementation in Python**:
   - Use `scipy.optimize.linprog` for solving LP problems.
   - Plot constraints and feasible regions using `matplotlib`.

3. **Graphical Solution**:
   - The constraints are plotted to visualize the feasible region.
   - The optimal solution is marked on the graph for clarity.

---

## **Files in This Project**
1. `maximize_profit.py` - Code for **Maximizing Profit for a Factory**.
2. `minimize_cost.py` - Code for **Minimizing Cost for a Manufacturer**.
3. `additional_problems.py` - Other LP problems such as resource allocation, advertising budget, etc.
4. `README.md` - Project documentation.
5. `requirements.txt` - Python dependencies.

---

## **How to Run the Code**

### **Prerequisites**
1. Install **Anaconda** or ensure Python (3.8+) is installed.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
   The file contains:
   ```plaintext
   scipy
   matplotlib
   numpy
   ```

### **Steps to Run**
1. Clone or download the repository:
   ```bash
   git clone https://github.com/your-repo/linear-programming-project.git
   cd linear-programming-project
   ```

2. Open **Jupyter Notebook** (recommended for interactive exploration):
   ```bash
   jupyter notebook
   ```

3. Open and execute the respective `.ipynb` files or `.py` scripts:
   - For **Maximizing Profit**:
     ```bash
     python maximize_profit.py
     ```
   - For **Minimizing Cost**:
     ```bash
     python minimize_cost.py
     ```

4. View the results in the terminal (optimal solutions) and plots (graphical visualization).

---

## **Detailed Example: Maximize Profit**
### **Problem Setup**
A factory produces two products, A and B, with resource constraints:
- Machine time: \(2x + 3y \leq 12\)
- Raw materials: \(x + 2y \leq 8\)

### **Solution**
1. Code solves using `scipy.optimize.linprog`.
2. Constraints are plotted to show the feasible region.
3. The optimal solution is identified both programmatically and graphically.

### **Output**
The script outputs:
- The optimal number of products \(x\) and \(y\).
- The maximum profit value.
- A graph showing the feasible region and optimal solution.

---

## **Instructions for Extending the Project**
1. Add new LP problems:
   - Define objective function coefficients and constraints in a similar format.
   - Use the existing code as a template.
2. Modify the visualization:
   - Adjust axis limits and labels for different scales.
   - Customize colors and styles for clearer representation.

---

## **Conclusion**
This project showcases how to model and solve LP problems effectively using Python. It demonstrates both programmatic and graphical approaches, making it a versatile tool for learning and applying optimization techniques in various fields like manufacturing, finance, and logistics.

For questions or contributions, feel free to open an issue or pull request in the repository!
