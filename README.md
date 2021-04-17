# githooks

githooks are hook commands to prevent unexpected git operation.

## Configuration

- `githooks.init=<bool>`: Initialization flag.
- `githooks.disabled=<bool>`: Disable all custom hooks in this repository.
- `githooks.initRepoScript=<path/to/file>`: Path to the initialize repository script. (default: `~/.gitinit_repository`)
