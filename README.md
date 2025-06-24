# OPTIMIZATION-MODEL-PROJECT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: HARSHIT MEHAN

*INTERN ID*: CT04DN1628

*DOMAIN*: DATA SCIENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/3f52f052-aed8-4fdb-83a2-489dd62fdf03)


Project Overview

This project addresses a classic business problem of optimizing the production mix to maximize profit while respecting resource constraints such as labor hours and raw materials. Using Linear Programming techniques and the Python library PuLP, we develop and solve a mathematical model that guides decision-making for product manufacturing. The goal is to determine the optimal quantity of each product to manufacture so that overall profit is maximized without exceeding available resources.


Problem Statement

In this scenario, a company produces two products, Product A and Product B. Each product requires a specific amount of labor hours and raw materials, both of which are limited. The company wants to maximize its profit by deciding how many units of each product to produce.


Constraints:

Labor: Maximum of 100 hours available
Material: Maximum of 80 kg available


Profit per unit:

Product A: $40
Product B: $50


Solution Approach
We modeled this problem as a Linear Programming (LP) optimization task using PuLP, a powerful and easy-to-use Python library for linear optimization.


Steps followed:

Define decision variables:
Variables representing the number of units to produce for each product.
Set up the objective function:
Maximize total profit = (Profit per unit of A × quantity of A) + (Profit per unit of B × quantity of B).

Add constraints:
Ensure total labor hours and materials used by products do not exceed available limits.

Solve the model:
Use PuLP’s solver to find the optimal production quantities.

Analyze the results:
Output the optimal product quantities, total profit, and resource utilization.


Key Results

Optimal Production Quantities:

Product A: X units
Product B: Y units
Maximum Profit: $Z

Resource Usage:

Labor hours used: 100 / 100 (fully utilized)
Materials used: 80 / 80 (fully utilized)

The results indicate that the company should fully utilize the available labor and materials to achieve maximum profitability by producing the calculated quantities of Product A and B.

