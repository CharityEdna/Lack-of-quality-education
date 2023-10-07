PROBLEM
Lack of quality education.

 SUBPROBLEM
1.	Overcrowded classrooms
2.	Unequal access to education
3.	High teacher retention
   
SUBSOLUTIONS
1. Creation of more classrooms and online classes.
2. Providing a support system to students who are financially unstable.
3. Tracking teacher attendance and improving teachers working conditions.
   
 SUBPROBLEMS
A)  VARIABLES
These store and manipulate data. They are like containers that hold values that can be used throughout a program. A variable has a name, value and can change during the execution of a programme.

Overcrowded classrooms
	Represent the maximum capacity of the classroom
	Represent the current number of students enrolled in the classroom.
	Indicate whether the classroom is overcrowded or not. This variable will be set to ‘true’ if the current enrolment exceeds the class capacity and ‘false’ otherwise.

 Unequal access to education 
	represent the total number of students in a given region.
	Indicate the number of students currently enrolled in the educational institution.
	Accessibility ratio. This will give the level of access to education in the region. It provides a measure of how many students have been able to access education compared to the total population.

High teacher retention
The percentage or rate of teachers who continue to remain employed at a specific educational institution or with a particular region. This variable provides an overall measure of teacher retention and can be calculated by dividing the number of retained teachers by the total number of teachers employed.

B) CONTROL STRUCTURES
These enable the flow and execution of code based on certain conditions or rules.

Overcrowded classrooms
	If else statement. We check if the number of students exceeds the class capacity, if it does, we set the “is crowded” variable to true otherwise, if the number of students is equal or below the class capacity, we set “is crowded” to false.
	While loop. This checks if the number of students exceeds the class capacity, as long as it does we keep executing a series of actions to execute the overcrowding.
	Repeat control structure. We repeat a series of actions to address overcrowding until the number of students is equal to or below the class capacity. After each action, we repeat the calculations to reflect changes.

 Unequal access to education.
	Switch case. We use this based on different access levels to education so that different actions are taken. The default case handles unexpected access levels.
	If else statement. This conditional statement checks if access to education is limited for a particular group or individual. If it is, an alternative education approach can be provided to ensure they receive some form of education. If access is not limited, the standard education can be continued.
	We can use a loop to continuously access and monitor the access to education. As long as access remains limited, the loop will provide necessary resources and monitor the changes until the limitation is resolved.

High teacher retention.
Using a Boolean an if condition will be in place to provide a given action to improve the teacher retention rate
# Actions to improve teacher retention
If teacherRetentionRate < 0.9:
# take necessary actions to improve teacher retention

FUNCTIONS TO BE USED 
Subproblem: Overcrowded classrooms
#Variables:
maxCapacity = 25
currentEnrollment = 0
isCrowded = false

#Check if the number of students exceeds the class capacity
if currentEnrollment > maxCapacity:
    isCrowded = true
else:
    isCrowded = false

# Repeat control structures to address overcrowding
while isCrowded:
    # Take necessary actions to address overcrowding

 # Update current enrollment and check if still crowded
    # (This section will be repeated until the classroom is no longer crowded)
#Function to get the current number of students enrolled
    currentEnrollment = getCurrentEnrollment()
    if currentEnrollment > maxCapacity:
        isCrowded = true
    else:
        isCrowded = false

Subproblem: Unequal access to education
# Variables:
totalStudents = 5000
enrolledStudents = 0
accessibilityRatio = 0.0

# Calculate accessibility ratio
accessibilityRatio = enrolledStudents / totalStudents

# Control structures based on access levels
switch (accessibilityRatio):
    case 0.0:
        # No students have access to education
        # Take necessary actions to address the lack of access
        break
    case 0.1 to 0.5:
        # Limited access for a particular group or individual
        # Provide alternative education approach
        break
    case 0.5 to 1.0:
        # Standard education can be continued.

#Loop to continuously monitor access to education
while accessibilityRatio < 1.0:
    # Monitor and provide necessary resources to improve access
    
# Update enrolled students and recalculate accessibility ratio
# Function to get the number of currently enrolled
    enrolledStudents = getEnrolledStudents()  students
    accessibilityRatio = enrolledStudents / totalStudents

Subproblem 3: High teacher retention
# Variables
teacherRetentionRate = 0.9
# Actions to improve teacher retention
if teacherRetentionRate < 0.9:
# Take necessary actions to improve teacher retention
    

