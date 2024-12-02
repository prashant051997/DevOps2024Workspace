# File Permissions in Linux

Linux uses a permission system to control who can read, write, or execute a file. Every file has three types of users:

1. **Owner**: The user who owns the file.
2. **Group**: A group of users who share the same permissions.
3. **Others**: All other users on the system.

### Types of Permissions
- `r`: Read permission (view file contents).
- `w`: Write permission (modify file contents).
- `x`: Execute permission (run the file as a program).

### Viewing Permissions
Use the `ls -l` command to view file permissions. For example:
```bash
-rwxr-xr--
