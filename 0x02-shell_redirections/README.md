# 0x02. Shell Redirections

This directory contains Bash scripts that demonstrate input/output redirection, file manipulation, and basic text-processing commands.

## Tasks

### 0. Hello World
**File:** `0-hello_world`

Prints "Hello, World" to standard output.

### 1. Confused Smiley
**File:** `1-confused_smiley`

Displays a confused smiley "(Ôo)'."

### 2. Let's Display a File
**File:** `2-hellofile`

Outputs the content of `/etc/passwd`.

### 3. What About 2?
**File:** `3-twofiles`

Outputs the contents of `/etc/passwd` and `/etc/hosts`.

### 4. Last Lines of a File
**File:** `4-lastlines`

Shows the last 10 lines of `/etc/passwd`.

### 5. I'd Prefer the First Ones, Actually
**File:** `5-firstlines`

Shows the first 10 lines of `/etc/passwd`.

### 6. Line #2
**File:** `6-third_line`

Displays the third line of the local file `iacta` (without using `sed`).

### 7. It's a Good File That Cuts Iron Without Making a Noise
**File:** `7-file`

Creates a file named `*"Best School"*$?*****:)` containing the text `Best School`.

### 8. Save Current State of Directory
**File:** `8-cwd_state`

Writes the output of `ls -la` to `ls_cwd_content` (overwrites if exists).

### 9. Duplicate the Last Line
**File:** `9-duplicate_last_line`

Duplicates the last line of the local file `iacta`.

### 10. No More Javascript
**File:** `10-no_more_js`

Deletes all regular `.js` files in the current directory and its sub‑directories.

## Repository Information

- **GitHub repository:** system_engineering-devops
- **Directory:** 0x02-shell_redirections

## Important Notes

- All scripts start with `#!/usr/bin/env bash`
- The second line of each script is a comment describing its purpose
- All scripts are executable
