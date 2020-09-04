# Hewlett-Hackard-Analysis


## ANALYSIS OVERVIEW
The purpose of the analysis is to select and analyze data for all employees that will be retiring soon and positions that will need to be replaced.


## PROCESS
•	We were given six separate tables/csv files that we had to to set up and join based on the primary and foreign keys.

•	We created new tables within the same database to exclude information that we did not necessarily need for the required analysis, specifically employees that will retire in the near future.

•	We then presented a summary table showing the number of employees by the title that will need to be replaced in the future. This is extremely helpful for HR department so they can plan their time and resources to meet the needs of the business.


## RESULTS

•	Hewlett-Packard is a large company with hundreds of thousands of data rows existing in database (300,024 in our case, if to be precise). 

![ALL DATABASE ENTRIES](https://github.com/jojobear2020/Hewlett-Hackard-Analysis/blob/master/Images/total_emp_numbers_all.PNG)

•	While the overall total number includes multiple duplicates for employees that were promoted or moved within departments, we factored that in in our analysis. The total number of current employees is over thirty thousand people.

![](https://github.com/jojobear2020/Hewlett-Hackard-Analysis/blob/master/Images/total_emp_numbers_current_v3.PNG)

•	Given the number of current employees and estimated retirement age, we came up with an estimate of number of employees that may potentially retire anytime soon. Obviously, this is just a rough estimate.  For this specific analysis we factored in employees DOB. Having theses estimates may help HR and managers to plan their hiring needs for each highlighted tite/positions. 

![](https://github.com/jojobear2020/Hewlett-Hackard-Analysis/blob/master/Images/retiring_titles_results.PNG)

•	Due to the ever-changing needs of the business world, employee training is essential and we were tasked to present a list of employees that may potentially need mentorship/ training in the near future. We were able to get that data quickly based on the data available to us and criteria presented by HR.

![](https://github.com/jojobear2020/Hewlett-Hackard-Analysis/blob/master/Images/mentorship_eligibility_results.PNG)

## SUMMARY
HR need to replace about 54K employees, as per information seen above.

![](https://github.com/jojobear2020/Hewlett-Hackard-Analysis/blob/master/Images/total_emp_numbers_retiring%20(2).PNG)

Given the number of all employees that may qualify for retirement soon, we saw that there is enough employees to mentor the next generation of employees. We have slightly under two thousands of those who may need or want to participate in the HR mentorship program. 

![](https://github.com/jojobear2020/Hewlett-Hackard-Analysis/blob/master/Images/mentorship_eligibility_total_count.PNG)



__________________________________________________________________________________________________________________

**“Tell me and I forget, teach me and I may remember, involve me and I learn.”**
**― Benjamin Franklin**
