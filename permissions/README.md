# Shell Permissions

This directory contains shell permission management scripts:

- `0-iam_betty`: Switches the current user to the user betty
- `1-who_am_i`: Prints the effective username of the current user
- `2-groups`: Prints all the groups the current user is part of
- `3-new_owner`: Changes the owner of the file hello to the user betty
- `4-empty`: Creates an empty file called hello
- `5-execute`: Adds execute permission to the owner of the file hello
- `6-multiple_permissions`: Adds execute permission to owner and group, and read permission to others
- `7-everybody`: Adds execution permission to owner, group and others
- `8-James_Bond`: Sets permissions to 007 (no permissions for owner/group, all for others)
- `9-John_Doe`: Sets the mode to 753 (rwxr-x-wx)
- `10-mirror_permissions`: Sets the mode of hello the same as olleh
- `11-directories_permissions`: Adds execute permission to all subdirectories only
