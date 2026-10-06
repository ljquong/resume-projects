## Interview Scheduling System
A Python tool I'm developing to automate club interview scheduling by parsing applicant availability and finding valid timeslots.

### Overview
The scheduling process involves collecting applicant availability, identifying which timeslots are valid, and assignment interviews while accounting for scheduling constraints.
This project works to automate that process by taking availability data parsed from HTML webpages, converting it into structured information, and evaluating possible interview timeslots.

### Current Implementation
- Fetches club executive and applicant availability data from HTML pages
- Parses participant names, timestamps, and availability data
- Converts timestamps into readable dates and times
- Identifies valid interview timeslots
- Accounts for interview duration by checking consecutive timeslots 

### Work In Progress
I'm working toward a more intelligent scheduling system that can: 
- Rank timeslots based on scheduling preferences, such as the earliest available time
- Ensure interviewer schedules are balanced
- Track scheduled interviews to prevent double-booking

### What I Learned
This project has given me experience working with semi-structured web data and streamlining a manual workflow through automation. It has also shown me how a seemingly simple task becomes more complex as additional constraints and competing priorities are introduced. 
