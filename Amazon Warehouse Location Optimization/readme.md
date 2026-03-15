# Amazon Warehouse Location Optimization using Linear Programming

This project solves a real-world logistics problem using optimization techniques in Python. The goal is to determine the most cost-effective warehouses to open and how products should be distributed to different cities.

This project was completed as part of my internship at CodTech IT Solutions.

## Problem Statement

Large companies like Amazon operate multiple warehouses to supply products to various cities. Opening warehouses and shipping goods involves significant costs.

The objective of this project is to:

Minimize the total cost of:
- Warehouse opening
- Product transportation

Subject to constraints such as:
- Each city's demand must be satisfied
- Warehouse capacity limits must not be exceeded
- Budget constraints must be respected

## Optimization Technique Used

Linear Programming is used to solve the warehouse location and shipment allocation problem.

The PuLP library in Python is used to formulate and solve the optimization model.

## Technologies Used

- Python
- PuLP
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Workflow

1. Define warehouses and cities
2. Specify warehouse opening costs
3. Define city demand and warehouse capacity
4. Create shipping cost matrix
5. Build Linear Programming model
6. Apply constraints and objective function
7. Solve optimization problem
8. Analyze results and visualize data

## Results

The optimization model determines:

- Which warehouses should be opened
- How many units should be shipped from each warehouse to each city
- The minimum total operational cost

## Visualization

The project also includes visualizations for:

- Warehouse opening cost comparison
- City demand distribution
- Shipment allocation

## Learning Outcomes

Through this project, I learned:

- How optimization techniques solve business problems
- How Linear Programming is applied in logistics
- How to build optimization models using Python
- How data visualization helps in understanding results

## Future Improvements

- Add sensitivity analysis
- Implement geographic visualization using maps
- Expand model with real-world datasets
- Build an interactive dashboard


