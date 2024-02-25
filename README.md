# Bug Reports
***************

**Here are a few Bug Report samples that I wrote while testing www.fieni.ro**
***************

**Title:**
Broken Link "Primaria"

**Priority & severity:**
P2 - Low

**Steps to reproduce:**
1. Go to [www.fieni.ro](https://www.fieni.ro)
2. In the top menu hover over "Primaria"
3. From the dropdown list click on "Conducerea"
4. Click on the “Primaria” link on top of the page

**Expected result:**
A new page should load with information about "Primaria".

**Actual result:**
The 404 HTTP error code appears.

***************

**Title:**
Presentation video is not working

**Priority & severity:**
P3 - Medium

**Steps to reproduce:**
1. Go to [www.fieni.ro](https://www.fieni.ro)
2. In the middle of the page click on the video play button 

**Expected result:**
As the text of the video area specifies, a presentation video should start.

**Actual result:**
On the main page, when clicking on play button, the video is not starting

***************

**Title:**
Broken logo images

**Priority & severity:**
P5 - Low

**Steps to reproduce:**
1. Go to [www.fieni.ro](https://www.fieni.ro)
2. In the middle of the page click on “Autorități/Instituții publice centrale” card

**Expected result:**
Each item in the list on the page should have a logo image.

**Actual result:**
When accessing “Autorități/Instituții publice centrale” page, the logo images for each link in the list are broken.

***************

**Title:**
Broken Link "Autoritățile publice locale"

**Priority & severity:**
P4 - Low

**Steps to reproduce:**
1. Go to [www.fieni.ro](https://www.fieni.ro)
2. In the top menu on the left click on "Autoritățile publice locale"
3. From the dropdown list choose "Primarul"
4. Click on the “Autoritățile publice locale” link on top of the page

**Expected result:**
A new page should load with information about "Autoritățile publice locale".

**Actual result:**
When trying to access "Autoritățile publice locale" page, we get the 404 HTTP error code.

***************

**Title:**
Broken Link "Termeni si Conditii"

**Priority & severity:**
P3 - Low

**Steps to reproduce:**
1. Go to [www.fieni.ro](https://www.fieni.ro)
2. On the top-left of the page click on the phone icon to go to "Contact"
3. Scroll all the way down at the bottom of the page and click on "Termeni si Conditii"

**Expected result:**
A new page should load with information about "Termeni si Conditii"

**Actual result:**
When trying to access "Termeni si Conditii" page, we get the 404 HTTP error code.


***************

**Here are a few Bug Report samples that I wrote for a Login functionality**
***************

**Priority & severity:**
P2 - High

**Title:**
Login is not working properly

**Steps to reproduce:**
1. Go to www.website.com/login
2. Add a correct user / pass

**Expected result:**
User should be able to login and taken to his profile page.

**Actual result:**
When trying to login with the correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Test Data:**
User: tester01 & pass: 123456

***************

**Priority & severity:**
P2 - High

**Title:**
 Verify if the login form works when rotating the screen during logging in

**Steps to reproduce:**
1. Go to www.onlinestore.com/login
2. Add correct user & password
3. Rotate the device screen from portrait to landscape mode and landscape to portrait
4. Press Login Button

**Expected result:**
Application should rotates normally and fields should still be filled with previously entered data. After Login Button is pressed the user should be logged in successfully.

**Actual result:**
When rotating from portrait to landscape, the text in the user field is lost and the user has to enter it again.

**Test Data:**
alexandru & Pass: parola123

**Status:**
IN PROGRESS (NEW, IN PROGRESS, DONE, REOPEN)

***************

**Priority & severity:**
P2 - High

**Title:**
 Check if Forgot Password functionality works as expected and an email with reset password link is sent.

**Steps to reproduce:**
1. Go to www.onlinestore.com/login
2. Press "Forgot Password" Button
3. Add an email address
4. Press "Recover" button
  
**Expected result:**
User should receive an email with a reset password link. That link should allow the user to create a new password.

**Actual result:**
After pressing the ""Recover" button and waiting 15 minutes, the user didn't receive any link to create a new password.

**Test Data:**
User: alexsmith@email.com

**Status:**
REOPEN (NEW, IN PROGRESS, DONE, REOPEN)

***************

***************

***************

***************

***************

***************

***************


***************


***************
