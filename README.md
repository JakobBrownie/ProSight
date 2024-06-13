# ProSight

- Prosight is an internal application that I worked on while interning for The Normandy Group. Due to this project being internal I can not share the code but can describe some of the things I worked on!
- Prosight is a project management software that encompasses time entry, project planning, expenses, time off, and managing users.

- Prosight web: Angular
    - Developed bug fixes and feature implementations on their web version of prosight using javascript, typescript and an SQL database.
    - Implmented things like email notifications when an expense report is submitted or approved/ denied. Email based on User's role, submitting sends to managment, approval/ denial sends to user that submitted the report.
    - Bug fixes that required SQL changes such as a user filter defaulting to unassigned rather than to the current user when an item is added on a project planning page.
    - UI fixes for thing such as scroll bars, removal/ deactivation of buttons based on parameters and general formatting. 

- Prosight mobile: Flutter
    - Developed their expenses page on their mobile version of prosight using dart and an SQL database
    - Implemented CRUD operations for the expense page, ability to create expense reports, display them on the page, edit and delete them and submit for approval/ denial.
    - Developed the UI of the page to allow for screen taps to access details of each expense report and the ability to add, edit or delete details.
    - Displayed all relevent information per each expense report based on who the current user was, which report was selected and if details had been selected, while adhering to a user friendly interface.
