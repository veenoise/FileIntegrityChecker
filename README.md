# File Integrity Checker

This is my project submission for roadmap.sh devops roadmap.

## Usage

Use `sudo` because current user might not have access to /var/log/ or any directory that needs root user. 

```
Usage: ./integrity-check [OPTIONS] FILE/DIRECTORY

OPTIONS:

init            Initializes and stores hashes of all log files in the directory
check           Check if hashes mismatch
update          Update log hashes
```

## Screenshots


Project URL: https://roadmap.sh/projects/file-integrity-checker