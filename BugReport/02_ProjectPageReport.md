
## Summary (Summarize the bug encountered concisely)
Create new project- page has an option 'Create black project' instead of 'Create blank project'. Typo error occured during coding the headers.



## Steps to reproduce     
    Navigate To Login Page  LoginUrl
    Input Username  UserName
    Input Password  Password
    Submit Login Form
    Verify Page Should Contain Welcome page	
    Navigate to project page NewProjectURL
	Choose way to create the project -> 


## What is the current bug behavior?
Option 1 says 'Create black project'. Bug is a typo and is not actively doing anything but may misguide end users. 
     

## What is the expected correct behavior?
Option 1 should say 'Create blank project'
     
## Relevant logs and/or screenshots

      

## Possible fixes
Headers on project creation options should be checked and typos fixed, especially on option 1 from 'black' to 'blank'


## Whom do you report/ Assign To/ Tags
	  /label ~bug ~reproduced ~needs-investigation 
      /cc @project-manager 
      /assign @qa-tester

## Priority
Minor
      
