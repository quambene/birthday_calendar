# Birthday calendar

For some regions like Germany, Google doesn't include birthdays from Google
Contacts in Google Calendar. This is the case even if Google Contacts is
specified as linked service (see <https://myactivity.google.com/linked-services>).

For that reason, generate a birthday calendar as follows:

1. Export contacts in Google CSV format from <https://contacts.google.com>
1. Place exported `contacts.csv` in this repo directory
1. Run script in this repo: `python3 birthday_calendar.py`
1. The calendar file `birthday_calendar.ics` is created
1. Create a new empty calendar at <https://calendar.google.com>
1. Import `birthday_calendar.ics` to this new calendar

This project is based on
<https://support.google.com/calendar/thread/283288526?hl=en&msgid=301775766>.
