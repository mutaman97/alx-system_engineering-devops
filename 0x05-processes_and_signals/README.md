# Processes and Signals

This project explores process management and signal handling in Bash using commands such as `ps`, `pgrep`, `pkill`, `exit`, and `trap`.

## Tasks

* **0. What is my PID**
  * [0-what-is-my-pid](./0-what-is-my-pid): Displays its own PID.

* **1. List your processes**
  * [1-list_your_processes](./1-list_your_processes): Lists currently running processes, including those without a TTY, in a user-oriented hierarchy.

* **2. Show your Bash PID**
  * [2-show_your_bash_pid](./2-show_your_bash_pid): Displays lines containing the `bash` keyword from the processes list.

* **3. Show your Bash PID made easy**
  * [3-show_your_bash_pid_made_easy](./3-show_your_bash_pid_made_easy): Displays the PID and process name of processes containing `bash`.

* **4. To infinity and beyond**
  * [4-to_infinity_and_beyond](./4-to_infinity_and_beyond): Displays `To infinity and beyond` indefinitely with a `sleep 2` delay.

* **5. Don't stop me now!**
  * [5-dont_stop_me_now](./5-dont_stop_me_now): Kills the process from [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) using `kill`.

* **6. Stop me if you can**
  * [6-stop_me_if_you_can](./6-stop_me_if_you_can): Kills the process from [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) using `pkill`.

* **7. Highlander**
  * [7-highlander](./7-highlander): Displays `To infinity and beyond` indefinitely, showing `I am invincible!!!` on receiving a `SIGTERM` signal.

* **8. Beheaded process**
  * [8-beheaded_process](./8-beheaded_process): Kills the process from [7-highlander](./7-highlander).

* **9. Process and PID file**
  * [100-process_and_pid_file](./100-process_and_pid_file): Creates `/var/run/myscript.pid`, displays `To infinity and beyond` indefinitely, and handles signals `SIGTERM`, `SIGINT`, `SIGQUIT`, or `SIGTERM`.

* **10. Manage my process**
  * [manage_my_process](./manage_my_process): Writes `I am alive!` to `/tmp/my_process` indefinitely.
  * [101-manage_my_process](./101-manage_my_process): Manages [manage_my_process](./manage_my_process) script with start, stop, restart options.

* **11. Zombie**
  * [102-zombie.c](./102-zombie.c): C program creating five zombie processes, displaying their PIDs.
