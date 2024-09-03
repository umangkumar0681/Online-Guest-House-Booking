# OGHBS
Online Guest House Booking System for IIT KGP
I. REGISTRATION SYSTEM: 
Test Case ID: OGHBS-001 
Test Case Name: Registration of New Users and Authentication Process: 
Purpose: 
To verify that the registration feature of the website is working as 
expected. 
Pre-conditions: 
The website is accessible via the internet. 
Test Steps: 
Navigate to the website's registration page. 
Enter a valid username and password. 
Provide a valid email. 
Provide all the other information including verification documents 
Click the Registration button. 
Test Report: 
Test Cases: 
1. Registering with a new username and email id that does not exist in 
the database: 
Input: username: New_user; password: newuser123; email: 
newuser@gmail.com; 
Output: New Registration successful 
2. Registering with an already existing email: 
Input: username: old_user; password: olduser123; email: 
newuser@gmail.com; 
Output: Registration not successful, email id alredy in use 
3. Registering with an already existing username 
Input: username: new_user; password: newuser123; email: 
notnewuser@gmail.com; 
Output: Registration not successful, username alredy in use 
Result: In all the three scenarios, the system showed expected output 
Status: Pass 
II. LOGIN SYSTEM: 
Test Case ID: OGHBS-002 
Test Case Name: Login Functionality  
Purpose: 
To verify that the login functionality of the website is working as 
expected. 
Pre-conditions: 
The user has a valid account on the website. 
The user has a valid username and password. 
Test Steps: 
Navigate to the website's login page. 
Enter a valid username and password. 
Click the login button. 
Test Cases: 
1. Username with matching password exists: 
Input: username: New_user, password: newuser123 
Output: Log In successful 
2. Valid username but password is wrong: 
Input: username: New_user, password: notnewuser123 
Output: Wrong password 
3. Invalid username: 
Input: username: old_user, password: notnewuser123 
Output: User does not exist 
Result: All three scenarios, gave expected output 
Status: Pass 
III. Room Availability: 
Test Case ID: OGHBS-003 
Test Case Name: Checking Room Availability 
Purpose: To verify that the functionality for checking room availability is 
working properly 
Pre-Conditions: Login with a valid account 
Test Steps: 
Enter the check-in and check-out dates  
Test Cases: 
1. Valid dates: User enters present or future dates, which are not more 
than three days apart 
Output: Shows the available rooms 
2. Invalid dates:  
a. Past dates:  
Output: Invalid input 
b. More than 3 days of stay: 
Output: Invalid input  
Test Result: Both scenarios gave positive results 
Status:  Pass 
IV. Food options: 
Test Case ID: OGHBS-004 
Test Case Name: Food options 
Purpose: To check if the food selection option is working properly 
Pre-Conditions: Successfully logged in with a  valid account and a room 
has been selected 
Test Steps: Select one of the food options available 
Test Cases: 
1. Food options selected: 
Output: Food option gets highlighted; fee gets added to the 
overall total 
2. Food options not selected: 
Output: Nothing gets highlighted, food cost fee is 0 
Test Results: Both scenarios give correct output 
Status: Pass 
V. Room booking and confirmation: 
Test Case ID: OGHBS-005 
Test Case Name: Room booking and confirmation 
Purpose: To check if the room booking option is working properly 
Pre-Conditions: Successfully logged in with a valid account and a room 
has been selected 
Test Cases: 
1. Selected Room is available: 
Output: Room booking confirmed 
2. Selected Room is unavailable: 
Output: Prompt for waiting queue, the user gets placed in the 
waiting queue 
Test Results: Both scenarios give correct output 
Status: Pass 
VI. Payment and refund: 
Test Case ID: OGHBS-006 
Test Case Name: Payment and refund 
Purpose: To check if the payment and refund system is working properly 
Pre-Conditions: Successfully logged in with a valid account and a room 
has been selected and booked 
Test Steps: Enter the details of the card 
Test Cases:  
1. Successful payment: 
Output: Booking confirmed and room booking status updated 
2. Unsuccessful payment: 
Output: User can retry payment 
3. Cancellation:  
Output: Cancellation confirmation, followed by refund status 
Test Results: All three scenarios give correct output 
Status: Pass 
VII. Waiting queue: 
Test Case ID: OGHBS-007 
Test Case Name: Waiting queue  
Purpose: To check if the booking queue option is working properly 
Pre-Conditions: Successfully logged in with a valid account and a 
unavailable room has been selected 
Test Cases: 
Unavailable room is selected: 
1. User accepts to be put in the waiting queue 
Output: User is placed in the waiting queue 
2. User refuses to be put in the waiting queue: 
Output: User does not get placed in the waiting queue, booking 
cancelled 
Once a user gets placed in the waiting queue, he/ she automatically gets 
placed in the room when it becomes available and they are next in line 
Test Results: Both scenarios give correct output 
Status: Pass 
VIII. Feedback feature:  
This feature has not been implemented yet.
