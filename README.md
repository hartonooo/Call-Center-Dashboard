# Call-Center-Dashboard
create MS.Excel dashboard for Call Center's performance
setting year 2020</br>
	<details>
	<summary><b>Dashboard</b></summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/dashboard.jpg">
	</details>
	
1. Open csv file and then extract it to new excel file
2. Check data for any inconsistent or missing values:
	- six empty customer data -> remove
	- 19.887 rows in call timestamp column have inconsistent date-month format --> create new column and fix it with date(year, month, day) function
		use this new column as call timestamp and remove previous call timestamp column
    
3. Check for any duplicates -> not found
4. Select all data and format to table. So if there's any data updates, we can just click refresh data
5. Split (and create new column) from call timestamp into day and month column. Use them as time filter in our dashboard
6. Split (and create new column) from call_center to city2 and state2. Use them as call center location in our dashboard

	<details>
	<summary>table</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/table.jpg">
	</details>
  
7. Create pivot tables for Calls, Avg_satisfaction_score, Avg_call_duration
      
	<details>
	<summary>pivot_1</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/calls%2C%20avg_satisfaction_score%2C%20avg_call_duration.jpg">
	</details>

8. Create pivot table for Call trend
	
	<details>
	<summary>call trend</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/call_trend.jpg">
	</details>	    

9. Create pivot table for Call channel

	<details>
	<summary>call channel</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/call%20_channel.jpg">
	</details>	

10. Create pivot table for Reason for calling
	
	<details>
	<summary>reason for calling</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/reason_for_calling.jpg">
	</details>	

11. Create pivot table for Response time

	<details>
	<summary>response time</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/response_time.jpg">
	</details>

12. Create pivot table for Call center location

	<details>
	<summary>call center location</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/call_center_location.jpg">
	</details>

13. Create Dashboard and slicers for day, month, reason, channel, sentiment, call center location

	<details>
	<summary>slicer</summary>
	<img src="https://github.com/mas-tono/Call-Center-Dashboard/blob/main/image/slicer.jpg">
	</details>
	



