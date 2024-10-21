# RMM-Apps

This repository contains scripts and applications used in conjunction with Fisher's Technology Remote Monitoring and Management (RMM) tools. These tools are designed to help automate tasks, manage system configurations, and improve overall IT operations efficiency.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts and Tools](#scripts-and-tools)
- [Contributing](#contributing)
- [License](#license)

## Overview

The RMM-Apps repository provides a suite of scripts and small applications that support IT automation and system management using Fisher's Technology RMM solutions. The tools are designed to automate various tasks like software deployment, monitoring, and system configurations, making IT administration more efficient.

## Installation

To install and use any of the scripts or tools in this repository:

1. Clone this repository using the following command:

    ```bash
    git clone https://github.com/Fisher-s-Technology/RMM-Apps.git
    ```

2. Navigate to the directory of the specific tool or script you want to use.
3. Follow the instructions for that particular tool or script as outlined in its respective section.

## Usage

Each tool or script may have specific usage instructions. You can refer to the respective script directories for detailed information on how to execute them. Generally, most scripts can be run via the command line using:

```bash
./script-name.ps1
```

Make sure to run the scripts with the appropriate permissions. Some scripts may require administrative rights or access to specific APIs.

### Example

For example, to run the `app-deployment.ps1` script:

```bash
./app-deployment.ps1 -AppName "AppName" -InstallPath "C:\Program Files\App"
```

For detailed parameters and usage, refer to the Help section within each script.

## Scripts and Tools

Here is a list of some of the main scripts and tools included in this repository:

- `app-deployment.ps1`: Automates application deployment on client systems.
- `system-monitor.ps1`: Monitors system performance and sends alerts when thresholds are exceeded.
- `software-updater.ps1`: Automatically updates software across multiple machines.

For a complete list, refer to the contents of this repository.
