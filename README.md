# ASPNET-Week-5

Created an unscaffolded viewmodel for User Profiles with Username and Age as the variables.

Both variables in the UserProfileViewModel have restrictions attached to them. Both fields are required for submitting the form. The age variable has a required range (1-120).

Added Create and Edit forms to the HomeController that append the UserProfileViewModel to an XML file. The file is saved to the programs root folder.

Added a view form that takes inputs for Username and Age (Both are required)



Added session states to the application builder


Copilot: I used it to tell me how to load an XML file and pass that information to the Index action so it can display a welcome message specifically for the user. 
