# ASPNET-Week-5

Created an unscaffolded viewmodel for User Profiles with Username and Age as the variables.

Added sample XML file to the Data folder

Both variables in the UserProfileViewModel have restrictions attached to them. Both fields are required for submitting the form. The age variable has a required range (1-120).

Added Create and Edit forms to the HomeController that append the UserProfileViewModel to an XML file. The file is saved to the programs root folder.

Added two options to the header "User Sign Up" and "Edit Profile"

Added a view form that takes inputs for Username and Age (Both are required)

Added a page for changing the username by replacing the XML file with a new one

Copilot: I used it to tell me how to load an XML file and pass that information to the Home/Index action so it can display a welcome message + Username
