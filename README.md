# APAssignment

$Assignment

$Assignment will help you get count of Males, Females, out-of-state students(non-IL) and sorting based on users choice

Look how interactive and easy it is to run
	
	import project into your Default Directory
	Directory Path with required parameters for results
	Example: ./test studentsassgn.text 3
			  (Home Directory)	(file to access for records)	(parameters to pass)

Features			  
- Be interactive
- Make things easier to get results

Executing Steps
- Copy it to the default home directory and make sure to use the example listed to run]

Steps involved while coding Assignment
- Declared required variables to store the result
- created a function by passing parameters including selected sort order option, filename, newfilename-to-be-created as creating function is that simple and easy to use.
				Example: uf_sort_order $response $1 newFile.txt
- Getting the count of Males, Females and out-of-students(non-IL)(using substrings with field locations) and storing in respective variables so based on users response we can display the result.
				Used substring, if fi condition to accomplish the task
- Based on selected response of user give them a choice to select a column number to sort, If the response is valid then call up the function which sorts and creates a new file.	
- Now, it prompts the user for optional sorting options (a simple 1-Yes or 2-No), based on the choice we can either proceed to sort or quit the program.
- Also, features instead of just erroring out with out any relevant message to user, it displays a message for user to exactly know what has happened that caused program to error out. 	

References:
-https://stackoverflow.com/
-https://www.thegeekstuff.com
-https://ryanstutorials.net/bash-scripting-tutorial
-https://www.ibm.com/developerworks/library/l-bash-parameters/index.html
-linuxcommand.org
