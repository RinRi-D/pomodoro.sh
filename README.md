# Pomodoro.sh

Simple, POSIX-compliant shell script for pomodoro technique.

## Setup

Every study session is 25 minutes with 5 minutes break and 20 minutes long break after every 4 study sessions by default. You can easily change any value in the shell script. Don't forget to change the ringtone to your favourite one. That's it! You're ready to go.

## Starting

Just run pomodoro.sh:

```bash
./pomodoro.sh
```

If you've killed pomodoro.sh after, let's say, 2 sessions, you can easily restore the number of sessions you've already done. Just specify the number of sessions as the first argument:
```bash
./pomodoro.sh 2
```