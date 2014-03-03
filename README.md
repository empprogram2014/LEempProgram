LEempProgram
============
This is the psuedoCode for the program
## 1. show menu. prompt user for option
## 2. for user input call needed function
##    a. menu 1: Show Employees
##          1. open database
##          2. show lines of database( ie: print the data line for line
##     b. menu 2: Add Employees
##         1. input employee data
##         2. add info to a list
##         3. return the list
##         4. add list to dictionary
##         5. tell the user the action was successful
##     c. menu 3: remove employee
##         1. open Employee Data
##         2. prompt for employee number ('all' to display list of employees)
##         3. get employee from employee data
##         4. display employee information, prompt if ok to delete
##            a. if yes delete the employee 
##            b. if no cancel
##         5. tell the user the action was successful
##         6. close the employee Data File
##     d. menu 4: promote/demote employee
##         1. open EmployeeData
##        2. prompt for employee number ('all' to display list of employees, and re-prompt for emp number)
##        3. get employee from EmployeeData
##        4. display info, prompt if ok to change? (y/n)
##            a. if yes
##                1. prompt user for new position
##                2. append employeeList[postition] with input
##                3. display updated information
##            b. if no, cancel, prompt user to try another employee number
##        5. close the Employee Data file
##    e. menu 5: Change Pay
##        1. open EmployeeData
##        2. prompt for employee number ('all' to display list of employees, and re-prompt for emp number)
##         4. display info, prompt if ok to change? (y/n)
##            a. if yes
##                1. prompt user for new payrate
##                2. append employeeList[payrate] with input
##                3. find key the matches employeeList[employeeNumber], replace with new employeeList
##                4. display updated information
##            b. if no, cancel, prompt user to try another employee number
##      
##        5. close the Employee Data file
##    f. quit()
##            1. if chosen, sys.exit
######## These are the basics, For naming of Functions, keep it straight foward. If a variable or function
############would make more sense named something else, specify the lines the varible name and it will be considered.
############ when the program is brought together, we need continuity.
############ 
######## Communication is key. If you are stuck, ask for help. If possible, show your work, what you did. And your thoughts on why you are doing it.
