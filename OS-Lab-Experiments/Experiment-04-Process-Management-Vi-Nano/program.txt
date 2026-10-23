EXPERIMENT 04
TITLE: LINUX PROCESS MANAGEMENT AND TEXT EDITORS (VI AND NANO)

AIM:
To study and execute Linux process-management commands and use the
vi and nano text editors to create, edit, and manage text files in Ubuntu.

PART A: PROCESS MANAGEMENT COMMANDS

1. Display processes associated with the current terminal:
       ps

2. Display detailed information about processes:
       ps aux

3. Monitor running processes in real time:
       top
   Press q to quit.

4. Search for a process by name:
       pgrep -a sleep
   This may show nothing if no sleep process is running.

5. Start a sample command in the background:
       sleep 300 &
   The shell prints a job number and process ID (PID).

6. List jobs started from the current shell:
       jobs

7. Bring the current background job to the foreground:
       fg
   If there are multiple jobs, use a job specifier such as `fg %1`.

8. Suspend a foreground process:
   Run:
       sleep 300
   Press Ctrl + Z to suspend it.

9. Resume a suspended job in the background:
       bg
   Check its state with:
       jobs

10. End the sample sleep job:
        jobs
        kill %1
    Replace %1 with the correct job number shown by `jobs`.
    Alternatively, use the PID shown when starting the process:
        kill PID
    Replace PID with the actual numeric process ID.

11. Check whether the sample process is still running:
        pgrep -a sleep

12. Show the current shell's process ID:
        echo $$

Note: Do not terminate unknown system processes. Use the sample sleep
command for practice. `kill` sends SIGTERM by default; a process may
take a moment to exit.

PART B: CREATE AND EDIT A FILE USING NANO

13. Create or open a file:
        nano nano-file.txt

14. Type some sample text, for example:
        This file was created using the nano editor.
        I am learning Linux process management.

15. Save the file:
    Press Ctrl + O, then press Enter.

16. Exit nano:
    Press Ctrl + X.

17. Display the saved file:
        cat nano-file.txt

Useful nano shortcuts:
    Ctrl + O  Save (write out)
    Ctrl + X  Exit
    Ctrl + W  Search
    Ctrl + K  Cut the current line
    Ctrl + U  Paste the cut text

PART C: CREATE AND EDIT A FILE USING VI/VIM

18. Create or open a file:
        vi vi-file.txt
    If `vi` is unavailable, try:
        vim vi-file.txt

19. Enter insert mode:
    Press i, then type:
        This file was created using the vi editor.
        I am practising insert and command modes.

20. Return to command mode:
    Press Esc.

21. Save and exit:
        :wq
    Type the command after pressing Esc, then press Enter.

22. Reopen the file if you want to practise editing:
        vi vi-file.txt
    Press i to edit, press Esc, then use :wq to save and exit.

Useful vi commands (press Esc first):
    i       Enter insert mode
    Esc     Return to command mode
    :w      Save the file
    :q      Quit if there are no unsaved changes
    :wq     Save and quit
    :q!     Quit without saving changes
    dd      Delete the current line
    u       Undo the last change

PART D: VERIFY THE FILES

23. List the files:
        ls -l

24. Display the nano file:
        cat nano-file.txt

25. Display the vi file:
        cat vi-file.txt

PRECAUTIONS:
1. Check process IDs before using kill.
2. Practise process termination only with the sample sleep command.
3. Use Esc before vi commands such as :wq.
4. Remember to save files before exiting if you want to keep changes.
5. Avoid using :q! unless you intend to discard unsaved changes.

RESULT:
Fill in after performing the experiment: Process-management commands
were executed and text files were created and edited using nano and vi/vim.
