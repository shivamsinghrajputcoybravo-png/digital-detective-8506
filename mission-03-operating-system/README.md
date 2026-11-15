# Mission 3: Understand the Operating System

## Task 3.1: Explore Your Operating System

| Information Explored | What It Tells You | Your Observation |
|---|---|---|
| Operating System / System Details | Shows the operating system and its version. | macOS (add your version from `sw_vers`) |
| Current Account Identity | Shows the currently active account. | [redacted] |
| Available and Used Storage | Shows used and available disk space. | [Add your privacy-safe observation] |
| System Activity Snapshot | Shows running processes and system activity. | [Add your observation] |

Commands used: `sw_vers`, `whoami`, `df -h /`, `top -l 1 | head -n 10`

## Task 3.2: Understand Processes

| Question | Answer |
|---|---|
| What is a process? | A process is a program that is currently running on a computer. |
| What does PID represent? | PID stands for Process ID. It is a unique number assigned to each running process. |
| Example 1 | Browser process, such as Safari or Chrome. |
| Example 2 | Text editor process, such as VS Code or TextEdit. |

Command used: `ps -axo pid,comm`

## Task 3.3: Understand Paths and Permissions

### Absolute Path and Relative Path

| Path Type | Meaning | Example |
|---|---|---|
| Absolute Path | The complete path starting from the root directory. | `/Users/[redacted]/digital-detective-XXXX/mission-03-operating-system/README.md` |
| Relative Path | A path specified relative to the current working directory. | `mission-03-operating-system/README.md` |

### File Permissions

| Permission | Meaning | Example |
|---|---|---|
| r - Read | Allows reading file contents. | Opening a text file. |
| w - Write | Allows modifying a file. | Editing a text file. |
| x - Execute | Allows running a file as a program. | Running a Python script. |

Command used: `ls -l`

## Task 3.4: Operating System Responsibilities

| OS Responsibility | Explanation | Example |
|---|---|---|
| Process Management | Manages running programs and processes. | Running Chrome and VS Code. |
| Memory Management | Allocates and manages RAM for programs. | Giving memory to a running application. |
| Device Management | Controls connected hardware devices. | Managing a keyboard or printer. |
| File Management | Organizes, stores and retrieves files. | Creating and moving files. |
| User Interface / Shell | Allows users to interact with the computer. | macOS desktop and Terminal. |
| Security and Permissions | Protects files and controls user access. | Read, write and execute permissions. |

## My Understanding

I learned that an operating system manages the computer's hardware and software. It handles running processes, memory, devices, files and user permissions. I also learned how to check system information, understand file paths and identify file permissions using Terminal.

## Difficulties Faced

[Write about any difficulty you actually faced and how you solved it.]

## Commands and Tools Used

- sw_vers
- whoami
- df -h /
- top
- ps
- pwd
- cd
- ls -l
- Terminal