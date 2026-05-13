# Change File Permissions

## Security Requirement

The organization does not allow others to have write access to files.

## Command Used

```bash
chmod o-w project_k.txt
```

## Purpose of the Command

The command removes write (`w`) permissions from the "others" category for the file `project_k.txt`.

- `o` refers to others
- `-w` removes write permissions

## Result

Unauthorized users can no longer modify the file.

## Example Updated Permissions

```bash
-rw-rw-r--
```

## Security Benefit

This change helps prevent unauthorized file modifications and improves file security.
