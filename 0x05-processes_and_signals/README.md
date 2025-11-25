# 0x05. Processes and signals

This directory contains Bash scripts demonstrating process management and signal handling in Linux.

## Tasks

### 0. What Is My PID?
**File:** `0-what-is-my-pid`

Bash script that displays its own Process ID (PID).

### 1. List Your Processes
**File:** `1-list_your_processes`

Bash script that displays a list of currently running processes showing all processes, including those without a TTY, in a user-oriented format with process hierarchy.

### 2. Show Your Bash PID
**File:** `2-show_your_bash_pid`

Bash script that displays lines containing the word "bash" from the process list, allowing you to easily see your Bash PID.

### 3. Show your Bash PID Made Easy
**File:** `3-show_your_bash_pid_made_easy`

Bash script that displays the PID and process name of processes whose name contains the word "bash".

### 4. To Infinity and Beyond
**File:** `4-to_infinity_and_beyond`

Bash script that displays "To infinity and beyond" indefinitely with a 2-second pause between iterations.

### 5. Don't Stop Me Now!
**File:** `5-dont_stop_me_now`

Bash script that stops the 4-to_infinity_and_beyond process using the kill command.

### 6. Stop Me if You Can
**File:** `6-stop_me_if_you_can`

Bash script that stops the 4-to_infinity_and_beyond process without using kill or killall.

### 7. Highlander
**File:** `7-highlander`

Bash script that displays "To infinity and beyond" indefinitely and responds to SIGTERM by displaying "I am invincible!!!".

**File:** `67-stop_me_if_you_can`

Modified version of 6-stop_me_if_you_can that kills the 7-highlander process.

### 8. Beheaded Process
**File:** `8-beheaded_process`

Bash script that kills the 7-highlander process using SIGKILL.

## Repository Information

- **GitHub repository:** system_engineering-devops
- **Directory:** 0x05-processes_and_signals

## Important Notes

- All scripts start with `#!/usr/bin/env bash`
- Second line is always a comment explaining what the script does
- All scripts are executable
