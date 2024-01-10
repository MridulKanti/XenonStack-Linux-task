# XenonStack-Linux-
## Overview

`internsctl` is a custom Linux command-line script designed to perform various system-related operations. It provides functionalities related to CPU information, memory details, user management, file information, and more.

## Usage

### Getting Started

1. Ensure that the script (`internsctl`) is in the correct directory.
2. Give execute permissions to the script: `chmod +x internsctl`

### Workflow and Architecture
For a detailed understanding of the workflow and application architecture, refer to the provided flowchart diagrams.

Requirements
Linux environment
Bash shell


### Commands
```
  ./internsctl cpu getinfo
  ./internsctl memory getinfo
  ./internsctl user create <username>
  ./internsctl user list
  ./internsctl user list --sudo-only
  ./internsctl file getinfo <file-name>

