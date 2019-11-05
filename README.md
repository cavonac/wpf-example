# kychallenge
##### by Christopher Canova
## From the interviewer:
As part of our interview process, I’d like to ask you to send me software code with unit tests so I could assess your skills. Please respond within approximately 48 hours.  __Please make sure that the code does not violate your confidentiality obligations to your former or current employer which probably prohibits you from sharing the code with outside parties.__ Please send your code for review, not spending more than a few hours, through GitHub (preferred) or zip file over email (or contact me if you would like to use an alternative).
<br/><br/>
Here is the requirement list of metrics that we are using it for code review:

- Readability/Maintainability/Testability
- Safe concurrency
- OOP/SOLID principals 
- Project layout/organization
<br/><br/>
An expected time to complete this would be about 1 hour.
<br/><br/>
Write a C# .NET GUI application that meets the following requirements:
<br/><br/>
- WPF or WinForms
- Contains a background thread that simply keeps track of the number of seconds that have passed since the application started.
  - Integer precision fine
  - This thread should not block the operation of the main UI thread.
  - **Note:** I’m specifically looking for a solution utilizing a thread.
- Contains the following controls on the user interface:
  - A display of the number of seconds since application start
  - A button that allows resetting the number of seconds since application start to zero
  - A text box that allows the user to specify an arbitrary integer value, and a button that immediately sets the timer to that value.
  - A text box that contains a number and a button that increments that number each time the button is pressed.
- Ensure that user input is properly validated.
- Unit tests exist for code that is unit testable.
<br/><br/>
Also: Include a description of alternative way(s) of implementing a timer like this that does not use another thread, but that also does not block the UI or cause other concurrency problems.
---
