# Step 1: Preparing Your Data
1. Clean the Data:  
   - Open the "Uncleaned DS Jobs" worksheet.
   - Remove duplicates, handle missing values, and ensure consistency in column names.

# 2. Create the Transform Tables:  
   - Sal By Role: Summarize the dataset by job role and calculate the average salary for each role.
   - Sal By State: Group data by state and count the number of data science jobs per state.
   - Sal By Size: Group by company size and find out which pays the highest salary.



# Step 2: Creating Pivot Tables
Now, create Pivot Tables to generate necessary insights.

 1. State with the Most Number of Data Science Jobs
   - Insert a Pivot Table.
   - Use State in the Rows field.
   - Use Job Count in the Values field (set it to Count).
   - Sort in descending order to see which state has the most jobs.

 2. Job Role with the Highest Average Salary
   - Insert a Pivot Table.
   - Use Job Role in the Rows field.
   - Use Average Salary in the Values field.
   - Sort in descending order to identify the highest-paying role.

 3. Which Company Size Pays the Highest?
   - Insert a Pivot Table.
   - Use Company Size in the Rows field.
   - Use Average Salary in the Values field.
   - Identify the size category that pays the highest.

 4. Sector Employing the Lowest and Highest Number of Data Science Jobs
   - Insert a Pivot Table.
   - Use Sector in the Rows field.
   - Use Job Count in the Values field.
   - Identify the lowest and highest employing sectors.

 5. Sector with Minimum and Maximum Average Salary
   - Insert a Pivot Table.
   - Use Sector in the Rows field.
   - Use Average Salary in the Values field.
   - Identify sectors with the lowest and highest salaries.


# Step 3: Creating the Dashboard
1. Insert Charts for Visualization
   - Column Chart for State with Most Jobs
   - Bar Chart for Job Role with Highest Salary
   - Pie Chart for Company Size Salary Comparison
   - Bar Chart for Sector Job Count
   - Scatter/Column Chart for Sector Salary Comparison

2. Insert Slicers
   - Click on any Pivot Table, then go to Insert → Slicer.
   - Add Slicers for Role Type, Size, and State to make the dashboard interactive.

3. Insert a Map (If available)
   - Select the Pivot Table with State-wise Data.
   - Go to Insert → Maps → Filled Map Chart.
   - Adjust formatting for clarity.

4. Design & Formatting
   - Apply color schemes.
   - Use consistent fonts.
   - Align visuals neatly.
   - Rename charts and slicers appropriately.


 Step 4: Finalizing
- Test slicers to check interactivity.
- Adjust visual elements for readability.
- Ensure charts dynamically update with slicers.

![image alt](https://github.com/adrianlabor19/adrianlabor19/blob/3cf13b0651291b8cdeb7c5d4c04caa05714f34d6/Midterm%20Task%203/dashboard.PNG)

