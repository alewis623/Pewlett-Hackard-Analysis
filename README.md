# Pewlett-Hackard-Analysis
## Overview of Analysis
Pewlett-Hackard is in a transistion, significant numbers of employees are of retirement age. This is an analysis of the employees elegible for retirement, what roles they have and how many employees are eligible to be potential mentors for new staff. 

## Resources

* Data Source: employees.csv, dept_emp.csv and titles.csv
* Software:  pgAdmin 4 Version 6.1, PostgreSQL 11.3

## Results

There are 90,398 employees that will soon be retiring. 29,414 Senior Engineers are nearing retirement. 28254 employees with the title of Senior Staff are also retireing soon.  

The complete employee list of employees are contained in the retirement_titles.csv. Please note that employees in this file will be represented more than once as they may have had multiple titles over the course of there Pewlett-Hackard career.

A unique list of employees with the most recent title is contained in the file unique_titles.csv. 

There are 1549 employees that are identified as potential mentors for incoming employees. This list of employees can be found in the data folder under mentorship_eligability.csv

## Summary

Significant numbers of retirements are in the Senior Engineers and Senior Staff titles. The 2 titles encompass 63.7% of the upcoming retirements. 

![image](https://user-images.githubusercontent.com/90878901/140675495-25a49bc0-93e0-4b79-950a-f07aa2bf65d2.png)

I would recommend Human Resources of Pewlett-Hackard work with leaders to identify both internal employees that could backfill these roles. They should also work with recruiters to find external canidates for these roles. There is a potential of needing to replace over 90,000 roles
An additional recommendation would be to identify the mentors from the mentorship_eligability.csv for candidates to work on the knowledge transfer before large scale retirements occur. The numbers of employees currently identified for mentorship is 1:58 ratio. More employees will need to be identified if leadership ultimately determines the need to replace every retirement role. 
