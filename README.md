# Pi_Ta


# **USER MANAGEMENT SCREEN**

## **1.Introduction**

The User Management Screen consist of three sections. The content of the page is detailed in the following items

   **1.1**   First section is located on the top of the page which includes both   'New User' &  'Save User' buttons. Additionally there has been checkbox which is selected default and provides hiding the disable users named "Hide Disabled User"

   **1.2**  Second section includes information table of users which located under the first section and left side of page. Includes **'ID'**, **'User Name'**, **'E-mail'**, **'Enabled'** fields on the first line as a title.

   **1.3** Third section includes text fields and comboboxes for new users information which located left side of the page. The fields are **'Username'**, **'Display Name'**, **'Phone'**, **'Email'**, **'User Roles'**, **'Enabled'**.

## **2.Details of User Management Screen  Components**

*   New User - *Button*
    *  Indicates an action for opening the new user information section
* Hide Disabled User - *Checkbox*
    * Allows the user to select for hiding disabled users
* Save User -*Button*
    * Indicates an action for saving the new user information
* User Table 
    * Shows fields for added to the table
    * Users can also filter each title
    * Ascending and descending sorting should be possible for each title  

|ID|User Name|E-mail|Enabled|
|--|---------|------|-------|
|1|Admin User|admin@piworks.net|true|
|2|Test User|testuser@piworks.net|true|

* New User Information Fields
    * Username - *Text Field*
    * Display Name - *Text Field*
    * Phone -*Text Field*
    * Email - *Text Field*
    * User Roles - *Dropdown List*
        * Guest
        * Admin
        * SuperAdmin
    * Enable - *Checkbox*

## 3.Business Rules 
### 3.1 Landing Page
 The Landing Page opens with first and second sections (1.1, 1.2). 
* New User Button should be active and able to click
* Hide Disabled User checkbox should be selected by default
* User Table should be contain existing data
* User Table data should be sorted by ascending ID by default
### 3.2 Adding New User
* New User button triggers New User Information Fields to open
* The following fields are required and the controls are described
    * Username: Should contain only text. If it contains special characters, a warning should be given on the screen such as "Please Enter Text Only"
    * Email: It should be checked that it is suitable for the email format. If it is not suitable for the format, a warning should be given on the screen such as "Please Check The Email Address"
    * User Roles: Should be selected according to the drop-down list
* The following fields are optional and the controls are described
    * Phone: Should contain numbers. If it contains other characters, a warning should be given on the screen such as "Please Check The Phone"
    * Enabled Checkbox: Must be selected if the user is to be activated. 
        * If the checkbox is selected, the result returns true otherwise false.
* After the relevant fields are filled, the save button becomes active.
* Clicking the Save button creates a new user.
* User information is added to the table



