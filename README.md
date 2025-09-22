# ASPNET-Week-5

Created an unscaffolded viewmodel for User Profiles with Username and Age as the variables.

Added sample XML file to the Data folder

Both variables in the UserProfileViewModel have restrictions attached to them. Both fields are required for submitting the form. The age variable has a required range (1-120).

Added Create and Edit forms to the HomeController that append the UserProfileViewModel to an XML file. The file is saved to the programs root folder.

Added two options to the header "User Sign Up" and "Edit Profile"

Added a view form that takes inputs for Username and Age (Both are required)

Added a page for "editing" the username by just replacing the XML file with a new one

Copilot: I used it to tell me how to load an XML file and pass that information to the Home/Index action so it can display a welcome message + Username

Test Plan:
1. Navigate to "/Home/Create".
2. Fill out the required fields in the form and click the submit button.
3. Look at welcome message and verify that the recent username that was input is correct.
4. Verify that the UserProfile.xml file saved in the root of the project folder.
5. Open UserProfile.xml to see if the information was appended correctly to the file.
6. Restart the application and see if the index loaded the xml correctly.
