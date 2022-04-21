# Process Management Commands

````bash
time 
````

````bash
ps
````
- Displays the currently =-running processes. Includes `PID`, `TTY`, `TIME`, and `CMD`
    - `PID` is the process ID.
    - `TTY` (teletype) is the file name of the standard input's terminal.
    - `TIME` is total accumulated CPU utilization time for the process.
    - `CMD` is the command that the process is executing.

````bash
kill [pid]
````
- Sends a `SIGTERM` to `pid` by default.