                                           #Overview of Project

We are exploring Pewlett Hackard employee data to design ERD and create an SQL database. We built an analysis around identifying the number of employees retiring by their title and employees eligible for the mentorship program. 

![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/employeeDB.png)
ERD diagram helps understand relationships between different tables corresponding to their primary keys. It also helps visually as a reference to figure out the joining process for tables.

                                               #Analysis

•	A retirement dataset was created, and we observed that there are duplicate values. Due to promotions, employees have had multiple titles over the years. 
![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/retirement_title.png)

•	To remove the duplicate entries from retirement titles. The DISTINCT ON function was used on the retirement title table and created a table named unique titles. 
![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/unique_titles.png)

•	We calculated the total number of individuals that are retiring from each department. 
![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/retiring_titles.png)

•	We also ran a query and built a table named mentorship eligibility. As shown below, we have 1,549 rows/ individuals that can train other employees.
![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/mentorship_eligibility.png)


                                                 #Summary

The number of employees at Pewlett Hackard is 300,024, and 72,458 employees will be retiring soon. Pewlett Hackard will have a 24% of its workforce deficit. A significant number of senior engineers (25,916 ) and senior staff (24,926) will be retiring soon, which can hurt the company’s day-to-day operations. To combat this crisis, Pewlett Hackard must develop a hiring and mentorship program. 

![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/total_emp.png)

Pewlett Hackard has 1,549 employees to become mentors to future employees. We can’t assume that everyone eligible for the program will be willing to participate. As we can see, 169 senior engineers and 569 senior staff are qualified for the mentorship program to train employees before the upcoming massive retirement trend. When we compare other positions, the numbers seem to be less. Based on the numbers, we can say there are not enough employees for the mentorship program.

![](https://github.com/smzd/Pewlett_Hackard_Analysis/blob/main/Resources/png_files/mentorship_eligibility_group.png)
