# Processes and Signals

## Description
This project contains Bash scripts that demonstrate process management, signals, process IDs, and background processes.

## Tasks
- `0-what-is-my-pid`: Displays the current process ID.
- `1-list_your_processes`: Lists running processes.
- `2-show_your_bash_pid`: Displays Bash processes.
- `3-show_your_bash_pid_made_easy`: Displays process IDs and names containing Bash.
- `4-to_infinity_and_beyond`: Prints a message continuously.
- `5-dont_stop_me_now`: Stops a running process using `kill`.
- `6-stop_me_if_you_can`: Stops a process without using `kill` or `killall`.
- `7-highlander`: Handles the SIGTERM signal.
- `67-stop_me_if_you_can`: Stops the `7-highlander` process.
- `8-beheaded_process`: Forcefully terminates the `7-highlander` process.
- `10-process_and_pid_file`: Demonstrates signal handling and PID files.
- `manage_my_process`: Writes `I am alive!` to `/tmp/my_process` every two seconds.
- `11-manage_my_process`: Starts, stops, and restarts `manage_my_process`.

## Requirements
- Bash
- Python is not required for these scripts.
- Ubuntu/Linux environment

## Usage
Make scripts executable with `chmod +x filename` and run each script from the project directory. Use `./11-manage_my_process start`, `./11-manage_my_process stop`, or `./11-manage_my_process restart` to manage the background process.`
