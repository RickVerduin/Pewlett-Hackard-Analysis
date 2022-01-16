# Pewlett Hackard Analysis

## Overview
### Background
PH is about to be hit with a "silver tsunami". A huge amount of employees are about to reach retirement age. To cope with the loss of experienced senior employees, a mentoring program has been developed. This program will keep retirees born in 1965 employed part-time and contribute to training and mentoring their replacements. 

### Method
In order to get the number of employees that are retirng, as well as the number of employees eligible for the mentoring program, six CSV-files with employee and department data have been combined into a database. The following schema was used to determine primary and secondary keys involved in building the database.

![EmployeeDB](https://user-images.githubusercontent.com/93882635/149643074-a8979c1c-b51c-4012-8b77-35f1940f4a0a.png)

After the database was completed, SQL queries were made ton extract the necessary data from the database.

##Results
- PH has a total of 72,456 employees that are about to retire
- Broken down by title, it is clear that the majority or retirees hold senior positions within the company. When these employees retire, it will lead to the loss of experience within the company

![image](https://user-images.githubusercontent.com/93882635/149643396-82143aae-e017-4b4c-9034-73c14ac2009b.png)

- Surprisingly, only two retirees are managers. 
- A total of 1549 retiring employees are eligible to participate in the mentorship program.

###Summary
Unless HP takes action, it will have to deal with the loss of 72,456 employees in the near future. The mentorship program may be a good start to deal with this situation, but even if every retiree eligible to become a mentor accepts the responsibility, they will be responsible for almost 50 mentees. For someone about to retire, and wanting to take it easy, taking 50 new hires under their wing, will be a daunting task. 

## Suggestions for additional queries
- To increase the number of eligible mentors, the query can be expanded to include retirees other than just the ones born in 1965. Increasing the range of birth dates will lead to more potential candidates.
- A query can be made to see how many former employees are about to hit retirement age. If PH can get former employees interested, it will increase the size of its mentor pool.
