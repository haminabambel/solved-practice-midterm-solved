Download Link: https://assignmentchef.com/product/solved-practice-midterm-solved
<br>
<u>The following tasks are to done in the indicated classes:</u>

Task #0 – (in the SalariedEmployee class and the HourlyEmployee class)

<ul>

 <li>Fix the error due to extending the Employee superclass

  <ul>

   <li>Note: the method for HourlyEmployee needs to get hours to compute weekly pay.</li>

  </ul></li>

 <li>Create the toString() method</li>

</ul>

Task #1 – Define an arrayList, myEmployees, of Employee type (in the EmployeeDemo class)

Task #2: (in the EmployeeDemo class)

Add a try-catch block to handle FileNotFound &amp; any general Exception

Add a finally clause, but check that the file was created before closing it

Task #3: (in the EmployeeDemo class)

Open the input file, stored in the project’s directory

Use a try-catch-finally block to handle the fileNotFound condition

Within the try-catch block:

read the salaryEmp.txt file until the end of the file(firstName, lastName, annualSalary)for each record read, create a SalariedEmployee object, and put inside arrayList of myEmployees

read the hourlyEmp.txt file until the end of the filefor each record read, create an HourlyEmployee object, and put inside myEmployees arrayList(firstName, lastName, wage)Task #4: (in the EmployeeDemo class)

Write a loop that, for each employee, will polymorphically display the employee’s data, ask the user for any missing data (hours), and then polymorphically calculate weeklyPay and display the pay.