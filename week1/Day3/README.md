# Day X - Managing Linux Processes

Today I learned how Linux handles running programs through processes.

## Topics Covered

- What a process is
- PID and process ownership
- Listing processes using ps, top, htop
- Foreground vs background jobs
- jobs, fg, bg
- Killing frozen processes using kill and pkill
- Changing priorities using nice and renice
- Introduction to cgroups
- Services managed with systemctl

## Commands Practiced

\`\`\`bash
ps
ps aux
top
jobs
sleep 60 &
fg
bg
kill PID
pkill name
nice
renice
systemctl status ssh
\`\`\`

## Mini Project

Built a process monitoring script that reports top CPU and memory processes.

## Reflection

Processes are the heartbeat of Linux systems. Understanding them is critical for troubleshooting servers and cloud environments.
