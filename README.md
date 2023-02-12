# Simple Pomodoro
This is a simple bash script that runs a pomodoro timer via notifications on Linux!

<center>
<img src="https://github.com/prayag2/pomo/blob/main/0.png" style="width: 40%;">
</center>

## Dependencies
- `libnotify` (for `notify-send`)

## Usage
```
Usage: pomo [options]
Options:
	-f <focus time in sec> (Default is 1500)
	-b <break time in sec> (Default is 300)
	-l <long break in sec> (Default is 1200)
	-r <number of sessions before long break> (Default is 4)
	-c <number of cycles> (Default is 1)
	-F <command to run when focus time starts>
	-B <command to run when short break starts>
	-L <command to run when long break starts>
	-E <command to run when program exist>
```
