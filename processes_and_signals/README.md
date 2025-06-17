# Processes and Signals Assignment

## Overview

This repository contains Bash scripts demonstrating Linux process management and signal handling concepts. The scripts help understand how to:

- Display process IDs (PIDs)
- List running processes
- Manage infinite loops
- Send and handle signals like SIGTERM and SIGINT
- Use signal traps to control process behavior

## Scripts Description
 0-what-is-my-pid      | Displays the current script’s Process ID (PID)           
 1-list_your_processes | Lists all running processes with detailed information        2-show_your_bash_pid  | Shows Bash processes without using `pgrep`                
 3-show_your_bash_pid_made_easy | Lists Bash PIDs and commands without using `ps`    
 4-to_infinity_and_beyond | Runs an infinite loop showing a message every 2 seconds    5-dont_stop_me_now    | Terminates the infinite loop using `kill` command           6-stop_me_if_you_can  | Stops the infinite loop without using `kill` or `killall`
 7-highlander          | Runs an infinite loop that traps signals 
 8-beheaded_process    | Sends signals to terminate the `7-highlander` process        10-process_and_pid_file | Demonstrates creating and managing a PID file with signal handling  

## How to Use

1. Make the script executable:

   chmod +x <script_name>
## Run the script by:

./<script_name>
