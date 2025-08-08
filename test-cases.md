Test case - TCID1
Title - Verify that user can reach website from browser
Preconditions - browsers (Chrome , Firefox , Edge)
Steps
1 - Open Chrome/Firefox/Edge browser 
2 - In the address bar tyoe URL - http://localhost:3000
3 - press enter 
Expected result  - The website is loads successfully and all UI elements are visible 

Test case - TCID2
Title - Verify that all UI elements in sign up form are visible and accessible 
Preconditions - User is not singed in system 
Steps
1 - Open website in browser 
2 - Navigate to the Sign up form 
3 - Observe for all UI element contains Sign up Form ( First name / Last name / Email/ Country / City/ Pasword / Repeat Password/ Sign Up button)
Expected result - All Ui elements are visible and accessible for users

Test case - TCID3
Title - Verify that Nav button is visible and redirects to the home page 
Steps
1 - open website in browser 
2 - Locate Nav Button (sportsbook)
3 - Click the Nav Button
Expected result Nav button is vissible and redirects to the home page 

Test case - TCID04
Title Verify that when on sign up page click login change the view 
Preconditions - no logged in user
Steps
1 - Open website in browser
2 - Navigate to Sign up form and click 
3 - Observe sign in form and find login form at the botttom 
4 - click on login form 
Expected result - Login button redirect to login form 

Test case - TCID5
Title - Verify that when you type password on Login form is hiden with symbol "*"
Preconditions - Not logged in user
Steps 
1 - open website in browser
2 - navigate to the login form 
3 - type your username and password
Expected result - Password is hiden with symbol "*" when is typing 

Test case - TCID6
Title - Log in with not valid password 
Precondtions - Not logged in user with active account 
Steps
1 - Open the website in browser 
2 - Navigate to login form 
3 - Type valid input for username 
4 - Type invalid input for password
5 - Click on login button
Expected result - The user is not able to log in system the messege apear "insert valid password"
