# Pewlett-Hackard-Analysis

## Overview 

The purpose of this analyisis is to use SQL to determine the number of  of retiring employees per title, and identify employees who are eligible to participate in a mentorship program to help the manager team to prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

## Results

-After the analyisis, we created a table (retiregave us the list of employees born bettween "1952 & 1955" and paired them with their job titles.

![image](https://github.com/gotica462/Pewlett-Hackard-Analysis/blob/main/Retirement_Titles.png)

- Since we have duplicates on the table we created an unique list using the DISTINCT ON()  function to remove duplicates

![image](https://github.com/gotica462/Pewlett-Hackard-Analysis/blob/main/Unique_Titles.png)

- We retrieved the number of employees by job title using the Group by function. 

![image](https://github.com/gotica462/Pewlett-Hackard-Analysis/blob/main/retiring_titles.png)

- We also created a table to identify employees who are eligible to participate in the mentorship program

![image](https://github.com/gotica462/Pewlett-Hackard-Analysis/blob/main/mentorship_program.png)

## Summary

Based on our analysis we determined that the "silver tsumanmy" will create more than 70,000 vacancies in the company. Most of them among senior staff members. Complicating matters worse is that about 1,500 people are only qualified to mentorship program, so clearly there are enough mentors to help fill those vacancies. 
One solution would be to allow more people to getiting into the mentorship program by lowering the age need to qualify, another solution would be to start recruiting young people and putting them into a trainning program using a clasroom model where one mentor could help more than 10 people at the same time







