# Solo Sprint: command-line user management

A menu-driven Python command-line app for managing user accounts. It loads
users from a CSV file, and supports login, checking account status, and
setting or changing passwords.

Built as a solo project during the DE-NAT4 data engineering bootcamp (April
2026), with the sprint's planning notes and screenshots included.

## How to run

```bash
python main.py
```

The app reads `users.csv` from the same folder. Columns are `username`,
`status` (`active` or `disabled`) and `password`.

## Files

```
main.py       the application: App, Menu and User classes and the main loop
users.csv     sample user data
*.png, *.jpg  screenshots from the sprint
```

## Known gaps

- Passwords are stored in plain text in `users.csv`. This is fine for a
  learning project, but a real system would store salted password hashes.
  Don't reuse any real password in the sample data.
- The sprint brief isn't included in this repo.
