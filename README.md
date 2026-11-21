### EX4 Implementation of Cluster and Visitor Segmentation for Navigation patterns
### REG NO: 212225230060
### DATE: 21/11/2026
### AIM: To implement Cluster and Visitor Segmentation for Navigation patterns in Python.
### Description:
<div align= "justify">Cluster visitor segmentation refers to the process of grouping or categorizing visitors to a website, 
  application, or physical location into distinct clusters or segments based on various characteristics or behaviors they exhibit. 
  This segmentation allows businesses or organizations to better understand their audience and tailor their strategies, marketing efforts, 
  or services to meet the specific needs and preferences of each cluster.</div>
  
### Procedure:
1) Read the CSV file: Use pd.read_csv to load the CSV file into a pandas DataFrame.
2) Define Age Groups by creating a dictionary containing age group conditions using Boolean conditions.
3) Segment Visitors by iterating through the dictionary and filter the visitors into respective age groups.
4) Visualize the result using matplotlib.

### Program:
```python
# Visitor segmentation based on characteristics
# read the data
/*WRITE YOUR CODE HERE

# Perform segmentation based on characteristics (e.g., age groups)
/*WRITE YOUR CODE HERE

```
### Output:
<img width="952" height="772" alt="image" src="https://github.com/user-attachments/assets/8d911b70-cfb7-487f-85b3-97e0760569de" />

<img width="913" height="567" alt="image" src="https://github.com/user-attachments/assets/2b1bf0e5-c271-4754-8076-78ced0b6b433" />

<img width="952" height="537" alt="image" src="https://github.com/user-attachments/assets/2ca53834-2520-4e7b-a3c9-63c36ac613d6" />


### Visualization:
```python
# Create a list to store counts of visitors in each age group
/*WRITE YOUR CODE HERE

# Count visitors in each age group
/*WRITE YOUR CODE HERE
    
# Define age group labels and plot a bar chart
/*WRITE YOUR CODE HERE

plt.figure(figsize=(8, 6))
plt.bar(age_group_labels, visitor_counts, color='skyblue')
plt.xlabel('Age Groups')
plt.ylabel('Number of Visitors')
plt.title('Visitor Distribution Across Age Groups')
plt.show()
```
### Output:
<img width="568" height="424" alt="image" src="https://github.com/user-attachments/assets/624be337-09cf-40e9-a592-b8cf03abfe2b" />


### Result:
Successfully implemented Cluster and Visitor Segmentation for Navigation patterns in Python.
