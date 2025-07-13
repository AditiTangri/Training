# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 9**

**Date:** 3 July 2025

## Mean, Median, and Mode in Python

We can use the `statistics` module from the Python standard library to calculate these measures:

1. **Mean**  
   The mean is the average:  
   - Adds all elements.  
   - Divides by the number of elements.

2. **Median**  
   The median is the middle value when the list is sorted:  
   - If odd number of elements: returns the middle one.  
   - If even number: returns the average of the two middle numbers.

3. **Mode**  
   The mode is the value that appears most frequently in the list:  
   - Example: In `[10, 20, 20, 30]`, the mode is `20`.

4. **Standard Deviation in Python**

   The standard deviation measures the spread (how much the values deviate from the mean).

    What does `statistics.stdev(data)` do?  
    - It calculates the **sample standard deviation**.


```python
import statistics

data = [10, 20, 20, 30]

mean_value = statistics.mean(data)
median_value = statistics.median(data)
mode_value = statistics.mode(data)
st_value = statistics.stdev(data)

print("Mean:", mean_value)
print("Median:", median_value)
print("Mode:", mode_value)
print("Standard Deviation : ",st_value)
```

---

## Percentile in Python

A **percentile** indicates the value below which a given percentage of observations in a dataset falls.

For example:  
- The 75th percentile is the value below which 75% of the observations may be found.

---

## Scatter Plot in Python

A **scatter plot** is used to visualize the relationship between two numerical variables.

### What is `matplotlib.pyplot`?

- `matplotlib` is a popular Python library used for data visualization.
- `pyplot` is a submodule in `matplotlib` that provides a MATLAB-like interface to create plots easily.
- The common alias `plt` is used so you can call functions like `plt.plot()`, `plt.scatter()`, `plt.show()`, etc.

### Installation

To install matplotlib, use:

```bash
pip install matplotlib
```

```python
import matplotlib.pyplot as plt

# Sample data
x = [1, 2, 3, 4, 5]
y = [5, 4, 3, 2, 1]

# Create scatter plot
plt.scatter(x, y)

# Add labels and title
plt.xlabel('X Axis')
plt.ylabel('Y Axis')
plt.title('Simple Scatter Plot')

# Show the plot
plt.show()
```

