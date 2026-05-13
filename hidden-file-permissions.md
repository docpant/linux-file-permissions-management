# Change File Permissions on a Hidden File

## Hidden File

```bash
.project_x.txt
```

## Security Requirement

The hidden file should:
- allow read access to the user and group
- remove write permissions for all users

## Command Used

```bash
chmod u=r,g=r,o= .project_x.txt
```

## Purpose of the Command

The command:
- gives read permission to the owner (`u=r`)
- gives read permission to the group (`g=r`)
- removes all permissions for others (`o=`)

## Example Updated Permissions

```bash
-r--r-----
```

## Security Benefit

This configuration protects the hidden archived file from unauthorized modifications while still allowing authorized users to view the file.
