# Copilot Instructions for set-se-103

## Project Overview
This is a shell scripting practice repository. It contains simple bash script exercises in the `advanced-shell-practice/` directory, each demonstrating different shell commands and patterns.

## Repository Structure
- `advanced-shell-practice/` - Contains numbered shell script exercises:
  - `0-copy_html` - Demonstrates file copying with `cp -u`
  - `1-whatsnext` - Demonstrates `grep` with pattern matching
  - `2-whatsnext` - Similar grep exercise
  - `test.html` - Test/target file for scripts
- `test.html` - Root level copy of test file
- Shell scripts are executable bash files (mode 755)

## Key Conventions
1. **Script Execution**: All exercises are shell scripts. Run them with `bash script_name` or `./script_name` if executable.
2. **Testing**: Scripts are designed to work with the `test.html` file. The `0-copy_html` script uses `cp -u` to copy HTML files from the `advanced-shell-practice/` directory to the parent directory.
3. **Git Hooks**: The repository uses Git LFS for tracking. The `.git/hooks/post-checkout` hook is configured for LFS.

## Build, Test, and Lint
This repository doesn't have automated builds, tests, or linters configured. It's a practice repository for learning shell scripting.

- **Manual Testing**: Execute individual scripts to verify behavior:
  ```bash
  cd advanced-shell-practice
  bash 0-copy_html
  bash 1-whatsnext
  ```

## Notes
- All shell scripts are in bash and should be POSIX-compliant where practical
- The `grep` exercises demonstrate basic pattern matching on `/etc/passwd`
- This is a learning repository, so scripts are simple and focused on single shell concepts
