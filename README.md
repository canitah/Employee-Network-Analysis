# Employee-Network-Analysis

##### Author: Qanitah Nizam

##### Date: November 25, 2022

# How can the company improve collaboration?
 
 
## Background
You work in the analytics department of a multinational company, and the head of 
HR wants your help mapping out the company's employee network using message data. 
They plan to use the network map to understand interdepartmental dynamics better 
and explore how the company shares information. The ultimate goal of this project 
is to think of ways to improve collaboration throughout the company.


## Questions To Answer
 1. Which departments are the most/least active?
 2. Which employee has the most connections?
 3. Identify the most influential departments and employees.
 4. Using the network analysis, in which departments would you recommend the HR team 
    focus to boost collaboration?
 
 ## Dataset
 1. Datacamp given dataset.
 2. It has 2 CSV.
 3. The data is complete and reliable.
 
 ## Data Cleaning - Change Log
 1. Removed duplicates and nulls.
 2. Split timestamp into date and time columns.
 3. Created new columns.
 4. Changed datatypes.
 
 ## Count of employees 
 In the graph below we can see company is most populated with the US and France employees.
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/count_emp.png" height="460" width="560" >
 
 ## Number of Employees in each department
 Sales and admin departments are most populated.
 
<img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/num_emp_dept.png" height="460" width="560"> 

 
 ## Merged Datasets
 Merged dataset into two separate files:
 1. senders_log - contains all the information about the sender
 2. receivers_log - contains all the information about the receiver
 
 ## USEFUL INSIGHTS
 
 ## Most Active Department
 By analyzing the dataset the Sales and the Operations Departments turned 
 out to be the most active departments in the company as they collaborated
 in the communication more than the other departments by sending out the most 
 number of messages. 
 Although in the graph above, we have seen the most populated departments were
 Sales and admin. This means admin department is lacking collaboration. 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/active_dpt.png" height="460" width="560" >
 
 
 ## Employee who has the 'Most Connections'
 The employee ID "598" communicated with the most number of distinct employees
 i.e. "77"
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/mostConnections.png" height="460" width="560" >
 
 
 
 ## The Most Influential Department & Employee
 A/c to given dataset the sales and operations department has sent and received 
 the most number of messages which makes them the most influential departments.
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/active_dpt.png" height="460" width="560" >
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/influential_dept.png" height="460" width="560" >
 
 Employee ID "605" is the most influential employee in the company as he sent 
 the most number of messages and also received good number of messages.
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/sentMostmsgs.png" height="460" width="560" >
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/recMostmsgs.png" height="460" width="560" >
 
 ## The Most Active Location 
 The employees based in US and France are the most collaborative, as shown in the 
 graph below:
 
 <img src="https://github.com/canitah/Employee-Network-Analysis/blob/main/images/ActiveLocation.png" height="460" width="560" >

 
 ## Reccomendations
 
 Company should Focus more on the marketing department as it is clear from the analysis that marketing 
 department was less collaborative.

 To improve collaboration company could:

  1. Create a supportive work environment.
  2. Communicate expectations clearly.
  3. Work with its employees' strengths.
  4. Encourage team members.
 
 
 

 
