# User Interface Specification Document
When the user runs the application, a screen should open where user creation can be performed. This screen should consist of 3 different parts. Operations to be performed in the header should be displayed, user information should be displayed in the right section, and new user creation should be performed in the left section. In the screen web view, the title should be displayed on top and the other sections side by side, and it should be displayed responsively on mobile or similar screen sizes.

![UI](https://github.com/shrgrl/UI-Spec/blob/master/img/img.png?raw=true)

## Header
Header should contain 3 different components. These; 
* User creation button-<i>New User</i> 
* Checkbox to show user information-<i>Hide Disabled User</i>
* User save button-<i>Save User</i>. 

Also, the Hide Disabled User checkbox must be checked at first startup and the Save User button must be inactive.

![UI](https://github.com/shrgrl/UI-Spec/blob/master/img/img1.png?raw=true)

## User Section
The users created and their information should be displayed here. This information should be kept in a table according to the ID, Usename, Email and Enabled information. If the user checks the Hide Disabled User checkbox, users with the Enabled status false should not be shown in the table. Additionally, filtering feature should be added to each column.

![UI](https://github.com/shrgrl/UI-Spec/blob/master/img/img2.png?raw=true)

## New User Section
In the New User section the user must create a new user. When creating a new user, Username, Display Name, Phone, Email fields should be filled with text fields, User Roles dropdown should contain 3 selections (Guest, Admin, SuperAdmin) and 'Select user roles...' text should be added with placeholder. Finally there should be a checkbox specifying the Enabled feature. After entering this information, the Save User button in the header should be activated and the user should click this button to save.

![UI](https://github.com/shrgrl/UI-Spec/blob/master/img/img3.png?raw=true)

