Kiss My Task

Very simple cli task manager. Just sqlite table and some scripts.

How to use:
1. Clone repo.
2. Copy kmt file to $HOME/.local/bin
3. Exec ```kmt init```
4. Exec ```kmt atd "My stupid task for today"```
5. Exec ```kmt vtd``` or ```kmt v```

Functions:

1. Add task (add this day - atd, add next day - and, add this week - atw, add next week - anw, add this month - atm, add next month - anm, add this year - aty, add next year - any, add life - al).
2. View tasks (view this day - vtd, etc)
3. Mark task completed (complete task - ct rowid).
4. Refresh statuses for expired tasks (update day - ud, uw, um, uy).
5. Add regular tasks. You can add your tasks in Update status expired tasks section.

Database structure:

- title - title
- desc - description
- dateTo - scheduled end date 
- type - scheduled time type (day, week, month, year, life)
- isExpired - is expired
- isCompleted - is completed
