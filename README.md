# confirmationEmailSAIO
  Script logic (Apps Script) to send confirmation emails in response to submitted event. This code is written to be used with Google Excel and Google Calendar to schedule events for increased organization of events and information. In resopnse to a submission from the Event Logging form, the Responses excel sheet updates, triggering the script to run. Information is pulled from the sheet and sent to corresponding parties through a personal email. NOTE: Stanford doesn't utilize google calendar, so a personal email is required to createEvent() in a Google Calendar.

# Possible improvements
- Reminder emails for receipt submission in the case that it isnt
- Link the Event logging form with the Receipt submission to auto-update information (Receipt submission, timing, types of purchases)
