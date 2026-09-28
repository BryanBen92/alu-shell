# Shell, processes and signals

Bash scripts covering PIDs, processes, signals and init scripts, written for the ALU shell project.

## Files

| File | Description |
|---|---|
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Lists all running processes with hierarchy in a user-oriented format |
| `2-show_your_bash_pid` | Displays the process lines containing `bash` (using `ps` and `grep`) |
| `3-show_your_bash_pid_made_easy` | Displays the PID and name of processes containing `bash` (without `ps`) |
| `4-to_infinity_and_beyond` | Displays "To infinity and beyond" indefinitely, with a `sleep 2` between each line |
| `5-dont_stop_me_now` | Stops `4-to_infinity_and_beyond` using `kill` |
| `6-stop_me_if_you_can` | Stops `4-to_infinity_and_beyond` without `kill` or `killall` |
| `7-highlander` | Displays "To infinity and beyond" and "I am invincible!!!" on SIGTERM |
| `67-stop_me_if_you_can` | Stops `7-highlander` without `kill` or `killall` |
| `8-beheaded_process` | Kills `7-highlander` with SIGKILL |
| `10-process_and_pid_file` | Creates `/var/run/myscript.pid`, handles SIGTERM, SIGINT and SIGQUIT |
| `manage_my_process` | Writes "I am alive!" to `/tmp/my_process` every 2 seconds |
| `11-manage_my_process` | Init script that starts, stops or restarts `manage_my_process` |

## Usage

Run the scripts from inside this directory, for example:

    ./0-what-is-my-pid
    ./11-manage_my_process start
    ./11-manage_my_process stop
