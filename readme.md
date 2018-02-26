# Auto Scheduler
This scheduler was intenteded to schedule CDA shifts automatically for IIT-RGL.
The main goal is to allow a supervisor to set a schedule on a calendar and set a date range where it is valid.

The information needed from the supervisor are:
+ The date range where the schedule will be valid for
+ Shift Times
+ Deadline by which the schedules should be submitted.
+ Assigned staff team

After the supervisor fills this information out, a spreadsheet will be populated by the information collected. The employees will recieve an email prompting them to open and fill out a form.

The employees will need to provide:
- How many hours a week they are willing to work for
- Their daily preferences for working
- Any expections for specific days which they do not wish to work for.

After initial responses are recieved the supervisor will have the option to run a process which will automatically populate a weekly spreadsheet from the responses recieved.

* * * 
## Workflow
- [x] Create a sample website 
- [ ] Collect basic information from the supervisor and save it to google sheets
- [ ] Prepare the full form so supervisors can send all the information (except visual shift aid)
- [ ] Allow supervisors to create Teams and see teams
- [ ] Create landing page
- [ ] Create user authentication and sign up for the service
- [ ] Make a graphical calendar UI where the supervisor can add shifts on a week

* * *

## Technologies Used 
- HTML/CSS/W3.CSS -> Website design
- Google Sheets API -> for saving schedules teams and everythin
- Python -> managing google sheets api
- JavaScript -> data comm

