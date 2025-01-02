# Basic-Shell
This project implements a basic shell (command-line interface) called LSH (Lightweight SHell) in C. It allows users to execute commands interactively, supporting built-in commands as well as external programs.

## Features
  - Built-in commands:
    -cd
    -help
    -exit
  -External command exectuion: Runs any excutable program available in the systems's path
  -Interactive prompt: Continuouly waits for user input until the exit command is issued

## How It Works
  1. Reading input: Reads the users prompt
  2. Parsing input: Splits the input into arguments for execution
  3. Executing commands:
    - Executes built-in commands directly
    -Launches external commands using the fork and execup system calls

## Compilation
  To compile the project, use the gcc compiler:
  gcc -o shell shell.c

## Usage
  ./shell
