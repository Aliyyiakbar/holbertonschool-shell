# Holberton School - Shell, permissions

This directory contains scripts focused on Linux permissions: chmod modes, ownership,
groups, and running commands as different users.

## Requirements

- OS: Ubuntu 22.04 LTS
- All scripts start with: #!/bin/bash
- All scripts are exactly 2 lines long
- No backticks, &&, ||, or ;
- All scripts are executable
- Note: some tasks must be done inside the sandbox to be corrected

## Tasks

- 0. My name is Betty — switch the current user to betty
- 1. Who am I — print the effective username of the current user
- 2. Groups — print all the groups the current user is part of
- 3. New owner — change the owner of a file
- 4. Empty! — create an empty file
- 5. Execute — add execute permission to the owner
- 6. Multiple permissions — add execute to owner/group and read to others
- 7. Everybody! — add execute permission to owner, group and others
- 8. James Bond — set permissions to 007
- 9. John Doe — set permissions to 753
- 10. Look in the mirror — set permissions of one file to match another
- 11. Directories — add execute permission to all subdirectories for owner/group/others
- 12. More directories — create a directory with specific permissions
- 13. Change group — change the group owner of a file
- 14. Owner and group — change owner and group for a file
- 15. Symbolic links — change owner and group of a symbolic link
- 16. If only — change owner of a file only if it’s owned by a specific user

## Usage

```bash
chmod u+x <script_name>
./<script_name>
```

## Author

Aliyyiakbar Shirinli
