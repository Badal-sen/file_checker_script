# File Checker Script

## Description
This shell script asks the user to enter a file name and checks whether the file exists or not.

## Features
- Takes file name input from user
- Checks if the file exists
- Displays result

## Commands Used
- echo
- read
- if
- else
- -f

## Script

```bash
#!/bin/bash

echo "Enter file name:"
read filename

if [ -f "$filename" ]
then
    echo "File exists"
else
    echo "File not found"
fi
