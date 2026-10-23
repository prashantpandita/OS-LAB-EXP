# Experiment 04: Linux Process Management and vi/nano Text Editors

## Aim
To study and execute Linux process-management commands and use the `vi` and `nano` text editors to create, edit, and manage text files in Ubuntu Linux.

## Requirements
- Ubuntu Linux installed on a computer or virtual machine
- Access to the Terminal
- `nano` and `vi`/`vim` text editors (availability may vary by installation)

## Commands and Editors Covered

### Process management
- `ps` and `ps aux` — display process information
- `top` — monitor processes and system resource usage interactively
- `jobs` — list jobs started in the current shell
- `sleep` — run a simple long-running command for practice
- `&` — start a command in the background
- `fg` and `bg` — bring jobs to the foreground or resume them in the background
- `kill` — send a signal to a process using its PID
- `pgrep` — search for processes by name
- `killall` — send a signal to processes by name, if installed

### Text editors
- `nano` — create and edit a text file using a beginner-friendly terminal editor
- `vi` or `vim` — create and edit a text file using a modal editor

## Procedure
1. Open the Ubuntu Terminal.
2. Run the process commands listed in `program.txt`.
3. Practise with the provided `sleep` command to observe foreground/background jobs.
4. Open `top` and press `q` to exit.
5. Create and edit a sample file using `nano`, then save and exit.
6. Create and edit another sample file using `vi` or `vim`, then save and exit.
7. Display the saved files using `cat` or `less`.
8. Capture screenshots of the commands, editor sessions, and results.
9. Save your screenshots in the `screenshots/` folder.

## Important Safety Notes
- Use the sample `sleep` process for practice rather than terminating an unknown system process.
- Check a process ID with `ps` or `pgrep` before sending it a signal.
- `kill` normally sends `SIGTERM` by default; avoid using `kill -9` unless genuinely necessary.
- In `vi`, press `Esc` before entering commands such as `:wq` or `:q!`.
- `:q!` exits without saving changes. Use it only when you intend to discard edits.
- Do not run commands with `sudo` for this experiment unless specifically required.

## Suggested Screenshots
- `01-ps-process-list.png`
- `02-top-process-monitor.png`
- `03-background-job.png`
- `04-nano-editor.png`
- `05-vi-editor.png`
- `06-saved-files.png`

Use screenshots captured from your own Ubuntu terminal.

## Result
Fill in after completing the experiment: Linux process-management commands were executed, and text files were created and edited using `nano` and `vi`/`vim`.

## Learning Outcomes
- Learned how to view and monitor Linux processes.
- Practised managing a sample foreground/background job.
- Learned how to send signals to a process safely.
- Practised creating, editing, saving, and viewing text files using `nano` and `vi`/`vim`.
