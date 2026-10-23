# Experiment 05: Shell Scripts Using Command-Line Arguments and Filename Manipulation

## Aim
To write and execute shell scripts that use command-line arguments to identify files and directories and perform filename manipulation.

## Requirements
- Ubuntu Linux or another Linux distribution
- Bash shell
- A terminal or command-line interface

## Programs included
1. `identify_path.sh` — accepts a path as an argument and identifies whether it is a regular file, directory, or another type of path.
2. `file_manipulator.sh` — accepts an operation and filenames as arguments to rename, copy, or change a file's extension.

## How to run
Open a terminal in this folder and make the scripts executable:

```bash
chmod +x identify_path.sh file_manipulator.sh
```

Run the path-identification script:

```bash
./identify_path.sh notes.txt
./identify_path.sh Documents
```

Run the filename-manipulation script:

```bash
./file_manipulator.sh rename old.txt new.txt
./file_manipulator.sh copy notes.txt notes_backup.txt
./file_manipulator.sh ext report.txt md
```

The `ext` operation changes `report.txt` to `report.md`. Supply the new extension without a leading dot.

## Safety notes
- Run these examples in a practice directory, not on important files.
- The script checks that source files exist and asks before overwriting a destination.
- Changing an extension changes the filename only; it does not convert the file's contents.

## Result
After running the scripts successfully, record the observed output and add your own terminal screenshots to the `screenshots/` folder.
