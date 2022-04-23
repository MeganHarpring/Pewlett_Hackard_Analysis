# Pewlett_Hackard_Analysis

## Overview of the analysis:

The purpose of this analysis is to help Pewlett Hackard determine different statistics about their employees so that they are better able to make hiring decisions and department placements. The manager at Pewlett Hackard wants us to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Ultimately, the manager needs to prepare for the "silver tsunami" as many current employees are reaching retirement age.

We will use different company tables/datebases to get the information we need to create different tables to show management which employees were born between January 1, 1952 and December 31, 1955 as these employees will be eligible to retire. We will also create a table that shows every employee's first and last name, employee number, and their most recent title. The third table we will creat to help Pewlett Hackard is a small table that just shows how many employees in each title are retiring. Lastly, we will create a table that shows employees born between January 1, 1965 and December 31, 1965 that are eligible for the mentorship program. 

## Results: 

1) If we wanted to create tables for the manager to provide him with the information he requested; we needed to look at the tables that we already have and figure out what columns we needed collectively to get the results we wanted, in order to do  this we needed to create an ERD. 

<img src="https://user-images.githubusercontent.com/100392991/164875043-1173e2a0-0698-4cb2-ae3f-bbaf7fe2a2c7.png" width="400">

2) The first table we used the ERD to create was the retirement_titles.csv but this table has many people listed more than once because they come up in different departments. We can edit the table so that everyone is only listed once but what the manager really needs to know is the total count of employees who are eligible to retire in each department so that they can make proper hiring decisions. The following table (retiring_titles.csv) was created to just show the count of employees in each department who could retire. 

<img width="200" alt="retiring_titles photo" src="https://user-images.githubusercontent.com/100392991/164879039-5c5cb491-f628-441e-a2d5-afa7be24aede.PNG">

3) Pewlett Hackard has almost 300,025 employees, in the table above you can see that 90,298 employees could possibly be retiring soon, that is 30.1%, they have a lot of hiring to do. Pewlett Hackard will need to hire a major amount of senior level employees, 64% of hirees will need to be senior level which typically is harder to find and takes longer to interview. This is important for the manager to know so that they can start this process soon and plan accordingly. 

4) Lastly, management wanted us to create a table that shows all employees born between January 1, 1965 and December 31, 1965. These employees are eligible for the mentorship program the company wants to start to help new hires get acclimated. This table (mentorship_eligibility.csv) snip-it below shows just part of the 1,550 employees who are eligible for the mentorship program. 

<img width="487" alt="mentorhsip snip" src="https://user-images.githubusercontent.com/100392991/164881461-91619a8d-aa52-4c97-ad66-4d94e8abc181.PNG">

## Summary: 

As the "silver tsunami" begins, upwards of 90k roles will need to be filled, now this won't all happen at once but over a 3-5 year period, lossing 90k employees is a BIG adjustment. Having so many new and younger employees will be tough but a good thing. New and younger employees can bring a lot of great ideas and changes to a company. I think a mentorship program is a great start to helping the company adjust to such changes in such a short period of time. 

The employees who are qualified to be mentors (those born in 1965, who will be getting ready to retire within the next 10 years) to those new incoming employees could have anywhere from 1-60 new employees. Not all 90k retirement ready employees will be retiring at the same time and not all of those roles will be filled at the same time so that is why I say each mentor would be responsible for anywhere from 1 to 60 new hirers. This is way too many. I think management needs to expand their mentorship eligibility to include a few more birth years around the 1965 birth year, maybe 1962-to 1955 since that is a 10 year difference from the retirement age range. 

We could adjust our management eligibility table time frame to include those born between January 1, 1962 to December 31, 1965 and see how many senior employees there are and depending on the result we can adjust our time frame for what we estimate the number of mentors we would need. 

Also, the company could send out an email to all those employees included in the retiring_titles table and ask them what their plans are for retiring (such as when), I would think it would even be smart to expand the time frame of that table to include all employees born before 1955 because there could be quite a bit of employees that are older (than birth year of 1952) that are planning on retiring and we are not even counting them.

