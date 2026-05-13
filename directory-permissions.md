# Change Directory Permissions

## Directory

```bash
drafts
```

## Security Requirement

Only the `researcher2` user should access the `drafts` directory and its contents.

## Command Used

```bash
chmod 700 drafts
```

## Purpose of the Command

The command assigns:
- full permissions to the owner
- no permissions to group members
- no permissions to others

## Example Updated Permissions

```bash
drwx------
```

## Security Benefit

Restricting access prevents unauthorized users from viewing or modifying sensitive directory contents.
