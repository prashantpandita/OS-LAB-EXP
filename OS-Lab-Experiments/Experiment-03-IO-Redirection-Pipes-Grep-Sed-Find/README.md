# Experiment 03: I/O Redirection, Pipes, and Linux Text-Processing Utilities

## Aim
To study input/output (I/O) redirection, pipes, and Linux utilities such as `grep`, `sed`, and `find` for file and text processing.

## Requirements
- Ubuntu Linux
- Access to the Terminal
- Basic familiarity with shell commands and text files

## Concepts Covered

- **Output redirection (`>`):** Sends command output to a file, replacing existing file contents.
- **Append redirection (`>>`):** Adds command output to the end of a file.
- **Input redirection (`<`):** Reads command input from a file.
- **Error redirection (`2>`):** Sends error output to a file.
- **Pipes (`|`):** Sends one command's output to another command as input.
- **`grep`:** Searches text for lines matching a pattern.
- **`sed`:** Processes text streams, including substitutions.
- **`find`:** Locates files and directories based on criteria.

## Procedure
1. Open Terminal in Ubuntu.
2. Create a practice directory and sample text file using the commands in `program.txt`.
3. Run the I/O redirection examples and inspect the created files.
4. Run the pipe examples and observe how one command's output becomes the next command's input.
5. Use `grep` to search for matching lines.
6. Use `sed` to replace text and print selected lines.
7. Use `find` to locate files by name and type.
8. Capture screenshots of the commands and their outputs.
9. Save your screenshots in this experiment's `screenshots/` folder.

## Safety Notes
- `>` overwrites an existing file. Use `>>` to append instead.
- `sed -i` edits files in place. Practise on a copy or use the non-destructive examples first.
- Check paths before using `find` with deletion actions. This experiment does not require deleting files.
- Commands and outputs can vary slightly by Ubuntu version and shell.

## Suggested Screenshots
- `01-io-redirection.png`
- `02-pipes.png`
- `03-grep-examples.png`
- `04-sed-examples.png`
- `05-find-examples.png`

Use screenshots captured from your own Ubuntu terminal.

## Result
Fill in after completing the experiment: I/O redirection, pipes, and the `grep`, `sed`, and `find` utilities were executed and their outputs were observed.

## Learning Outcomes
- Understood standard input, standard output, and standard error redirection.
- Learned to combine commands using pipes.
- Practised searching text with `grep`.
- Practised text substitution and line selection with `sed`.
- Learned to locate files and directories using `find`.
