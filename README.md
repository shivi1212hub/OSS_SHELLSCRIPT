# OSS_SHELLSCRIPT
Student Name: Shivi Sanjay
--
Registration Number: 24BAI10054

A collection of Linux shell scripts created for practicing open-source concepts, Linux system administration, and Bash scripting.

This repository contains small utility scripts that inspect and report information about a Linux system, including package details, disk usage, logs, permissions, and system identity.
## Repository Structure

```text
OSS_SHELLSCRIPT/
│
├── System_Identity.sh
├── DiskPermission_Auditor.sh
├── Log_Analyser.sh
├── Package_Inspector.sh
├── Manifesto.sh
├── .gitignore
└── README.md
```

## Scripts Included

### 1. System_Identity.sh

Displays basic information about the Linux system, including:

* Linux distribution name
* Kernel version
* Current logged-in user
* Home directory
* System uptime
* Current date and time
* Open-source license information

### 2. DiskPermission_Auditor.sh

Audits important system directories and reports:

* Disk usage
* Ownership of directories
* Security permissions
* Potential permission-related concerns

Directories checked include:

* `/etc`
* `/var/log`
* `/home`
* `/usr/bin`
* `/tmp`

### 3. Log_Analyser.sh

Analyzes Linux log files and extracts useful system information such as:

* Recent login attempts
* System errors
* Warning messages
* Activity from important logs

Useful for understanding how Linux logging works and identifying unusual activity.

### 4. Package_Inspector.sh

Inspects installed software packages on a Linux system and reports details such as:

* Package name
* Installation status
* Version information
* Package source

### 5. Manifesto.sh

Displays a short open-source manifesto or message explaining the importance of:

* Open-source software
* Community contribution
* Software freedom
* Linux and collaborative development

---

## Requirements

* Linux operating system
* Bash shell
* Basic Linux utilities such as:

  * `uname`
  * `whoami`
  * `uptime`
  * `df`
  * `du`
  * `ls`
  * `grep`
  * `awk`

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/shivi1212hub/OSS_SHELLSCRIPT.git
cd OSS_SHELLSCRIPT
```

2. Give execution permission to the scripts:

```bash
chmod +x *.sh
```

3. Run any script:

```bash
./System_Identity.sh
```
