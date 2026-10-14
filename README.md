# Shell Scripting - Day 1 Machine Test

## Student Details

- **Student Name:** Boby
- **Batch:** 9:15 PM
- **Date:** 10/13/2026

## Scripts

| Script | Description |
|--------|-------------|
| `welcome.sh` | Prints a simple welcome message ("Welcome to Linux" and "Learning Shell Scripting") using `echo`. |
| `student.sh` | Stores student details (name, course, batch) in variables and prints them. |
| `userinfo.sh` | Takes interactive input with `read` (name and course) and prints a personalised welcome message. |
| `systeminfo.sh` | Displays the current user, home directory and default shell using the environment variables `$USER`, `$HOME` and `$SHELL`. |
| `report.sh` | Uses command substitution to capture the current date (`date`) and logged-in user (`whoami`) into variables, then prints them. |
| `automation.sh` | Generates a basic server report showing the current date and time, current user, system uptime (`uptime`) and disk usage (`df -h`). |

## How to Run

Make a script executable and run it:

```bash
chmod +x welcome.sh
./welcome.sh
```

Or run it directly with bash:

```bash
bash welcome.sh
```

## Repository Structure

```
shell-scripting-day1-machine-test/
├── welcome.sh
├── student.sh
├── userinfo.sh
├── systeminfo.sh
├── report.sh
├── automation.sh
└── README.md
```
