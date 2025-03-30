# Process Monitor with Shiny

## Project Overview
This project is a web-based application built with R and the Shiny framework. It enables users to monitor running processes on a Windows machine and terminate specific processes by providing their Process ID (PID). The app uses interactive tables for process visualization and provides an intuitive interface for managing system processes.

---

## Features
1. **Process Monitoring**:
   - Displays the list of all running processes including their PID, session details and memory usage.
   - Utilizes a DataTable for an interactive and user-friendly display.

2. **Process Termination**:
   - Allows users to terminate a specific process by entering its PID.
   - Displays success or error messages based on the termination outcome.

3. **Real-Time Updates**:
   - Automatically refreshes the list of processes after a process is terminated.

---

## Installation and Setup
To use this application, follow these steps:

1. **Prerequisites**:
   - Install R on your system.
   - Install the following R packages:
     - `shiny`
     - `DT`
     - `dplyr`

   It can be installed using:
   ```R
   install.packages(c("shiny", "DT", "dplyr"))
