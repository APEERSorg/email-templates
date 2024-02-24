# Purpose
Stores all html code for every email template APEERS sends.

# How to Commit
1. Create a new folder for each email template.
1. Create a file called `template.html` and `var.txt` in the folder.
1. `template.html` contains the html code for the email template, write all code here.
1. `var.txt` contains the variables that will be replaced in the `template.html` file. Write all variables here. You can use your variables in the `template.html` file by using the following syntax: `{{variable_name}}`. This is more for documentation. Write a description of the variable as well in the `var.txt` file. Here is an example of what the `var.txt` file should look like:
```
{{first_name}}: The first name of the user.
{{last_name}}: The last name of the user.
{{email}}: The email of the user.
```