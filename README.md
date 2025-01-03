# Supermarket Shelf Space Optimization

## Overview
Efficient shelf space allocation is critical for enhancing supermarket profitability. This project presents an optimization model aimed at allocating products to shelves while addressing real-world constraints such as shelf capacity, product demand, and fragility. The methodology employs Mixed-Integer Linear Programming (MILP) for strategic decision-making.

---

## Objective
The primary goal of this project is to maximize revenue through optimized product placement. The optimization model incorporates factors like:
- **Shelf Constraints**: Capacity, height, and weight.
- **Product Characteristics**: Demand, space usage, fragility, and turnover.
- **Customer Satisfaction**: Ensuring product availability and enhancing the shopping experience.

---

## Methodology
1. **Problem Formulation**:
   - Defined decision variables, constraints, and the objective function.
   - Focused on maximizing profitability.

2. **Data Simulation**:
   - Simulated product-specific details like demand, profit margins, and physical constraints.

3. **Optimization Technique**:
   - Utilized MILP, solved using Pyomo/GLPK, to determine the optimal product placement.

4. **Constraints**:
   - Shelf space capacity.
   - Fragility and weight considerations.
   - Visibility and accessibility.
   - Diversity requirements for better customer experience.

---

## Key Features
- **Scalable Model**: The approach is adaptable to various retail environments.
- **Enhanced Insights**: Provides detailed allocation of products per shelf.
- **Profit Maximization**: Balances operational efficiency with increased revenue.

---

## Results
The MILP model output specifies:
- The exact quantity of each product to be placed on each shelf.
- Allocation ensuring compliance with all defined constraints.

---

## Technology Stack
- **Programming Language**: Python
- **Optimization Library**: Pyomo
- **Solver**: GLPK

---

## Conclusion
This project highlights the potential of optimization techniques in retail management. The formulated model enhances profitability, minimizes operational costs, and provides a customer-centric approach to product allocation. The methodology and results demonstrate the practical applicability of optimization in improving supermarket operations.

---

## Contributors
- 24N0465
- 24N0456
- 24N0461
- 24N0463
