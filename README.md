# Data Visualization Basics

A daily repository documenting the fundamentals of data visualization. This includes simple concepts, tools, and practical examples to get started with creating insightful visualizations.

## Topics Covered
- What is Data Visualization?
- Why is it important?
- Tools for Data Visualization (Excel, Tableau, Power BI, Python).
- A basic example using Python and Matplotlib.

## Example Code
Here’s a Python script for creating a simple bar chart:

```python
import matplotlib.pyplot as plt

# Define data
categories = ['A', 'B', 'C', 'D']
values = [4, 7, 2, 5]

# Create bar chart
plt.bar(categories, values, color='blue')

# Add title and labels
plt.title('Simple Bar Chart')
plt.xlabel('Categories')
plt.ylabel('Values')

# Show plot
plt.show()
