# Call-Center-Dashboard
create MS.Excel dashboard for Call Center's performance
setting year 2020

1. Open csv file and then extract it to new excel file
2. Check data for any inconsistent or missing values:
	- six empty customer data -> remove
	- 19887 rows in call timestamp column have inconsistent date-month format --> create new column and fix it with date(year, month, day) function
		use this new column as call timestamp and remove previous call timestamp column
    
3. Check for any duplicates -> not found
4. Select all data and format to table. So if there's any data updates, we just click refresh data
5. Split (and create new column) from call timestamp into day and month column. Use them as time filter in our dashboard
6. Split (and create new column) from call_center to city2 and state2. Use them as call center location in our dashboard

    <details>
    <summary>table</summary>
    <img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/table.jpg"
    </details>
  
7. Create pivot tables Calls, Avg_satisfaction_score, Avg_call_duration
      
    <details>
    <summary>pivot_1</summary>
    <img src="[https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/table.jpg](https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/calls%2C%20avg_satisfaction_score%2C%20avg_call_duration.jpg)"
    </details>

8.       
